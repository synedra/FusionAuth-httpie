<!-- TOP -->
<div class="top">
  <img class="scenario-academy-logo" src="https://cdn.prod.website-files.com/617b1b1f42c1da41aeae3413/6573599a9ea8c6ccef655afd_primary-logo.png" />
  <div class="scenario-title-section">
    <span class="scenario-title">Jump in to FusionAuth</span>
    <span class="scenario-subtitle">ℹ️ For technical support, please contact us via <a href="mailto:kirsten.hunter@fusionauth.io">email</a></span>
  </div>
</div>

<!-- NAVIGATION -->
<div id="navigation-top" class="navigation-top">
 <a href='command:katapod.loadPage?[{"step":"intro"}]'
   class="btn btn-dark navigation-top-left">⬅️ Back
 </a>
<span class="step-count"> Step 1 of 3</span>
 <a href='command:katapod.loadPage?[{"step":"step2"}]' 
    class="btn btn-dark navigation-top-right">Next ➡️
  </a>
</div>

<!-- CONTENT -->

<div class="step-title">Check your Keys</div>

# Check your keys

```
http :9011/api/key
```

You can see the keys that have been set up for your account here.  The kickstart for this module created the key you need to perform different actions, and they are automatically included in the `http` commands given here.

## Create a new user 

Create a new user with a random ID

```
http POST :9011/api/user
```

Create a new user with a specific ID

```
http POST :9011/api/user/myuserid
```

## Register user for application

- On the screen that follows, click "Add registration" to register the user for your application.
- Select "Example App" and then click the blue Save button at the top right of the page.
- Click on the command below to switch to the ChangeApp application

```
gp preview `gp url 3000`
```


<!-- NAVIGATION -->
<div id="navigation-bottom" class="navigation-bottom">
 <a href='command:katapod.loadPage?[{"step":"intro"}]'
   class="btn btn-dark navigation-bottom-left">⬅️ Back
 </a>
 <a href='command:katapod.loadPage?[{"step":"step2"}]'
    class="btn btn-dark navigation-bottom-right">Next ➡️
  </a>
</div>

