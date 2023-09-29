 <head>
    <meta charset="utf-8">
    <title>Conduit</title>
    <link rel="stylesheet" href="css/style.css">
    <link href="http://code.ionicframework.com/ionicons/2.0.1/css/ionicons.min.css" rel="stylesheet" type="text/css">
    <link href="https://fonts.googleapis.com/css?family=Titillium+Web:700|Source+Serif+Pro:400,700|Merriweather+Sans:400,700|Source+Sans+Pro:400,300,600,700,300italic,400italic,600italic,700italic" rel="stylesheet" type="text/css">
  </head>
  <body>
        <a class="navbar-brand" href="index.html">conduit</a>
        <ul class="nav navbar-nav pull-xs-right">
          <li class="nav-item">
            <a class="nav-link" href="editor.html">
              <i class="ion-compose"></i>&nbsp;New Post
            </a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="auth.html">Sign up</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="settings.html">Settings</a>
          </li>
<!--           <li class="nav-item active">
            <a class="nav-link" href="index.html">Home</a>
          </li> -->
        </ul>
      </div>
    </nav>
        <div class="feed-toggle">
          <ul class="nav nav-pills outline-active">
            <li class="nav-item">
              <a class="nav-link disabled" href="#">Your Feed</a>
            </li>
            <li class="nav-item">
              <a class="nav-link active" href="#">Global Feed</a>
            </li>
          </ul>
        </div>
          <div class="post-meta">
            <a href="profile.html"><img src="http://i.imgur.com/Qr71crq.jpg" /></a>
            <div class="info">
              <a href="profile.html" class="author">Eric Simons</a>
              <span class="date">January 20th</span>
            </div>
            <button class="btn btn-outline-primary btn-sm pull-xs-right">
              <i class="ion-heart"></i> 29
            </button>
          </div>
          <a href="post.html" class="preview-link">
            <h1>How to build webapps that scale</h1>
            <p>In my demo, the holy grail layout is nested inside a document, so there's no body or main tags like shown above. Regardless, we're interested in the class names and the appearance of sections in the markup as opposed to the actual elements themselves. In particular, take note of the modifier classes used on the two sidebars, and the trivial order in which they appear in the markup. Let's break this down to paint a clear picture of what's happening...</p>
            <span>Read more...</span>
          <div class="post-meta">
            <a href="profile.html"><img src="http://i.imgur.com/N4VcUeJ.jpg" /></a>
            <div class="info">
              <a href="profile.html" class="author">Albert Pai</a>
              <span class="date">January 20th</span>
            </div>
            <button class="btn btn-outline-primary btn-sm pull-xs-right">
              <i class="ion-heart"></i> 32
            </button>
          </div>
          <a href="post.html" class="preview-link">
            <h1>The song you won't ever stop singing. No matter how hard you try.</h1>
            <p>In my demo, the holy grail layout is nested inside a document, so there's no body or main tags like shown above. Regardless, we're interested in the class names and the appearance of sections in the markup as opposed to the actual elements themselves. In particular, take note of the modifier classes used on the two sidebars, and the trivial order in which they appear in the markup. Let's break this down to paint a clear picture of what's happening...</p>
            <span>Read more...</span>
          <p>Popular Tags</p>
          <div class="tag-list">
            <a href="#" class="label label-pill label-default">programming</a>
            <a href="#" class="label label-pill label-default">javascript</a>
            <a href="#" class="label label-pill label-default">angularjs</a>
            <a href="#" class="label label-pill label-default">react</a>
            <a href="#" class="label label-pill label-default">mean</a>
            <a href="#" class="label label-pill label-default">node</a>
            <a href="#" class="label label-pill label-default">rails</a>
          </div>
        </div>
      </div>

### Login/Register

```html

<div class="auth-page">
  <div class="container page">
    <div class="row">

      <div class="col-md-6 col-md-offset-3 col-xs-12">
        <h1 class="text-xs-center">Sign up</h1>
        <p class="text-xs-center">
          <a href="#">Have an account?</a>
        </p>

<!--         <ul class="error-messages">
          <li>That email is already taken</li>
        </ul> -->

        <form>
          <fieldset class="form-group">

### Profile

```html


<div class="profile-page">

  <div class="user-info">

        <div class="posts-toggle">
          <ul class="nav nav-pills outline-active">
            <li class="nav-item">
              <a class="nav-link active" href="#">My Posts</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">Favorited Posts</a>
            </li>
          </ul>
        </div>

        <div class="post-preview">
          <div class="post-meta">
            <a href="profile.html"><img src="http://i.imgur.com/Qr71crq.jpg" /></a>
            <div class="info">
              <a href="profile.html" class="author">Eric Simons</a>
              <span class="date">January 20th</span>
            </div>
            <button class="btn btn-outline-primary btn-sm pull-xs-right">
              <i class="ion-heart"></i> 29
            </button>
          </div>
          <a href="post.html" class="preview-link">
            <h1>How to build webapps that scale</h1>
            <p>In my demo, the holy grail layout is nested inside a document, so there's no body or main tags like shown above. Regardless, we're interested in the class names and the appearance of sections in the markup as opposed to the actual elements themselves. In particular, take note of the modifier classes used on the two sidebars, and the trivial order in which they appear in the markup. Let's break this down to paint a clear picture of what's happening...</p>
            <span>Read more...</span>
          </a>
        </div>

        <div class="post-preview">
          <div class="post-meta">
            <a href="profile.html"><img src="http://i.imgur.com/N4VcUeJ.jpg" /></a>
            <div class="info">
              <a href="profile.html" class="author">Albert Pai</a>
              <span class="date">January 20th</span>
            </div>
            <button class="btn btn-outline-primary btn-sm pull-xs-right">
              <i class="ion-heart"></i> 32
            </button>
          </div>
          <a href="post.html" class="preview-link">
            <h1>The song you won't ever stop singing. No matter how hard you try.</h1>
            <p>In my demo, the holy grail layout is nested inside a document, so there's no body or main tags like shown above. Regardless, we're interested in the class names and the appearance of sections in the markup as opposed to the actual elements themselves. In particular, take note of the modifier classes used on the two sidebars, and the trivial order in which they appear in the markup. Let's break this down to paint a clear picture of what's happening...</p>
            <span>Read more...</span>
          </a>

### Settings

```html

<div class="settings-page">
  <div class="container page">
    <div class="row">

        <form>
          <fieldset class="form-group">
            <input class="form-control" type="text" placeholder="URL of profile picture">
<!--             <input type="file" id="file"> -->
          </fieldset>
          <fieldset class="form-group">
            <input class="form-control form-control-lg" type="text" placeholder="Your Name">

    </div>
  </div>
</div>

```

### Create/Edit Article

```html


<div class="editor-page">
  <div class="container page">
    <div class="row">

### Article

```html


<div class="post-page">

  <div class="banner">

      <h1>How to build webapps that scale</h1>

      <div class="post-meta">
        <a href="profile.html"><img src="http://i.imgur.com/Qr71crq.jpg" /></a>
        <div class="info">
          <a href="profile.html" class="author">Eric Simons</a>
          <span class="date">January 20th</span>
        </div>
        <button class="btn btn-sm btn-outline-secondary">


    <div class="row post-content">
      <div class="col-md-12">
        <p>Web development technologies have evolved at an incredible clip over the past few years. </p>
      </div>
    </div>


      <div class="post-meta">
        <a href="profile.html"><img src="http://i.imgur.com/Qr71crq.jpg" /></a>
        <div class="info">
          <a href="profile.html" class="author">Duvi</a>
          <span class="date">September 29th</span>
        </div>
            <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
          </div>
          <div class="card-footer">
            <a href="profile.html" class="comment-author">
              <img src="http://i.imgur.com/Qr71crq.jpg" class="comment-author-img" />
            </a>
            &nbsp;
            <a href="profile.html" class="comment-author">Jacob Schmidt</a>
            <span class="date-posted">Dec 29th</span>
          </div>
        </div>
	
            <p class="card-text">With supporting text below as a natural lead-in to additional content.</p>
          </div>
          <div class="card-footer">
            <a href="profile.html" class="comment-author">
              <img src="http://i.imgur.com/Qr71crq.jpg" class="comment-author-img" />
            </a>
            &nbsp;
            <a href="profile.html" class="comment-author">Jacob Schmidt</a>
            <span class="date-posted">Dec 29th</span>
            <span class="mod-options">
              <i class="ion-edit"></i>
	@@ -479,6 +468,4 @@
  </div>

</div>

```