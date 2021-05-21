<script>
    let isactive = "";
    function modal(){
        if (isactive == "") {isactive="is-active"} else {isactive=""}
    }
</script>

<p>Right click then "Inspect" <span class="tag is-dark">Dark</span>
    <span class="tag is-light">Light</span>
    <span class="tag is-white">White</span>
    <span class="tag is-primary">Primary</span>
    <span class="tag is-link">Link</span>
    <span class="tag is-info">
        Info
        <button class="delete is-small"></button>
      </span>
<span class="tag is-success">Success</span>
<span class="tag is-warning">Warning</span>
<span class="tag is-danger">Danger</span>
</p>
<div class="tags has-addons">
    <span class="tag">One</span>
    <span class="tag is-primary">Two</span>
    <span class="tag">Three</span><a class="tag is-delete"></a>
  </div>
<a class="button is-primary">
    Button
  </a>
  <a class="button is-link">
    Button
  </a>
  <a class="button is-info is-small is-outlined">
    Button
  </a>
  <a class="button is-success is-loading">
    Button
  </a>
  <a class="button is-warning is-medium">
    Button
  </a>
  <a class="button is-danger is-large">
    Button
  </a>
  <button class="button is-black">Black</button>
    <button class="button is-info is-light">Info</button>
    <button class="button is-success is-light">Success</button>
    <button class="button is-warning is-light">Warning</button>
    <button class="button is-danger is-light">Danger</button>

  <button class="button is-outlined">Outlined</button>
<button class="button is-primary is-outlined">Outlined</button>
<button class="button is-link is-outlined">Outlined</button> <button class="button is-rounded">Rounded</button>
<button class="button is-primary is-rounded">Rounded</button>
<button class="delete"></button>
<div class="notification is-danger is-light">
    <button class="delete"></button>
    Lorem ipsum dolor sit amet, consectetur adipiscing elit lorem ipsum dolor sit amet, consectetur adipiscing elit
  </div>

  <div class="icon-text">
    <span class="icon has-text-info">
      <i class="fas fa-info-circle"></i>
    </span>
    <span>Information</span>
  </div>
  
  <p class="block">
    Your package will be delivered on <strong>Tuesday at 08:00</strong>.
  </p>
  
  <div class="icon-text">
    <span class="icon has-text-success">
      <i class="fas fa-check-square"></i>
    </span>
    <span>Success</span>
  </div>
  
  <p class="block">
    Your image has been successfully uploaded.
  </p>
  
  <div class="icon-text">
    <span class="icon has-text-warning">
      <i class="fas fa-exclamation-triangle"></i>
    </span>
    <span>Warning</span>
  </div>
  
  <p class="block">
    Some information is missing from your <a href="#">profile</a> details.
  </p>
  
  <div class="icon-text">
    <span class="icon has-text-danger">
      <i class="fas fa-ban"></i>
    </span>
    <span>Danger</span>
  </div>
  
  <p class="block">
    There was an error in your submission. <a href="#">Please try again</a>.
  </p>

  <span class="icon-text">
    <span class="icon">
      <i class="fas fa-train"></i>
    </span>
    <span>Paris</span>
    <span class="icon">
      <i class="fas fa-arrow-right"></i>
    </span>
    <span>Berlin</span>
    <span class="icon">
      <i class="fas fa-arrow-right"></i>
    </span>
    <span>Barcelona</span>
    <span class="icon">
      <i class="fas fa-arrow-right"></i>
    </span>
    <span>Paris</span>
    <span class="icon">
      <i class="fas fa-flag-checkered"></i>
    </span>
  </span>
<br/>
<br/>

<p> <a href="https://bulma.io/documentation/elements/box/">https://bulma.io/documentation/elements/box/</a></p>

<div class="box">
    <article class="media">
      <div class="media-left">
        <figure class="image is-128x128">
          <img class="is-rounded" src="https://bulma.io/images/placeholders/128x128.png" alt="Image">
        </figure>
      </div>
      <div class="media-content">
        <div class="content">
          <p>
            <strong>John Smith</strong> <small>@johnsmith</small> <small>31m</small>
            <br>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Aenean efficitur sit amet massa fringilla egestas. Nullam condimentum luctus turpis.
          </p>
        </div>
        <nav class="level is-mobile">
          <div class="level-left">
            <a class="level-item" aria-label="reply">
              <span class="icon is-small">
                <i class="fas fa-reply" aria-hidden="true"></i>
              </span>
            </a>
            <a class="level-item" aria-label="retweet">
              <span class="icon is-small">
                <i class="fas fa-retweet" aria-hidden="true"></i>
              </span>
            </a>
            <a class="level-item" aria-label="like">
              <span class="icon is-small">
                <i class="fas fa-heart" aria-hidden="true"></i>
              </span>
            </a>
          </div>
        </nav>
      </div>
    </article>
  </div>

<form class="box">
    <div class="field">
      <label class="label">Email</label>
      <div class="control">
        <input class="input" type="email" placeholder="e.g. alex@example.com">
      </div>
    </div>
  
    <div class="field">
      <label class="label">Password</label>
      <div class="control">
        <input class="input" type="password" placeholder="********">
      </div>
    </div>
  
    <button class="button is-primary">Sign in</button>
  </form>

  <nav class="breadcrumb is-centered" aria-label="breadcrumbs">
    <ul>
        <li>
            <a href="#">
              <span class="icon is-small">
                <i class="fas fa-book" aria-hidden="true"></i>
              </span>
              <span>Documentation</span>
            </a>
          </li>
      <li><a href="#">Components</a></li>
      <li class="is-active"><a href="#" aria-current="page">Breadcrumb</a></li>
    </ul>
  </nav>

  <div class="notification is-primary">
    <button class="delete"></button>
    Primar lorem ipsum dolor sit amet, consectetur
    adipiscing elit lorem ipsum dolor. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur.
  </div>
  <progress class="progress is-warning is-large" value="75" max="100">75%</progress>

  <p class="title is-1">Title size 1</p>
<p class="subtitle is-3">Subtitle size 3</p>


Forced columns on Mobile:
<div class="columns is-mobile">
    <div class="column">1</div>
    <div class="column">2</div>
    <div class="column">3</div>
    <div class="column">4</div>
  </div>
Auto (responsive)
<div class="columns">
    <div class="column">
      First column
    </div>
    <div class="column">
      Second column
    </div>
    <div class="column">
      Third column
    </div>
    <div class="column">
      Fourth column
    </div>
  </div>

  <div class="columns">
    <div class="column is-four-fifths">is-four-fifths</div>
    <div class="column">Auto</div>
    <div class="column">Auto</div>
  </div>
  
  <div class="columns">
    <div class="column is-three-quarters">is-three-quarters</div>
    <div class="column">Auto</div>
    <div class="column">Auto</div>
  </div>
  
  <div class="columns">
    <div class="column is-two-thirds">is-two-thirds</div>
    <div class="column">Auto</div>
    <div class="column">Auto</div>
  </div>
  
  <div class="columns">
    <div class="column is-three-fifths">is-three-fifths</div>
    <div class="column">Auto</div>
    <div class="column">Auto</div>
  </div>
  
  <div class="columns">
    <div class="column is-half">is-half</div>
    <div class="column">Auto</div>
    <div class="column">Auto</div>
  </div>
  
  <div class="columns">
    <div class="column is-two-fifths">is-two-fifths</div>
    <div class="column">Auto</div>
    <div class="column">Auto</div>
  </div>
  
  <div class="columns">
    <div class="column is-one-third">is-one-third</div>
    <div class="column">Auto</div>
    <div class="column">Auto</div>
  </div>
  
  <div class="columns">
    <div class="column is-one-quarter">is-one-quarter</div>
    <div class="column">
        <button class="button is-primary is-large modal-button" on:click={modal} data-target="modal" aria-haspopup="true">Launch example modal</button>
        <div class="modal {isactive}">
            <div class="modal-background"></div>
            <div class="modal-content">
              Modal content
            </div>
            <button class="modal-close is-large" aria-label="close" on:click={modal}></button>
          </div>
    </div>
    <div class="column">
        <article class="message">
        <div class="message-header">
          <p>Hello World</p>
          <button class="delete" aria-label="delete"></button>
        </div>
        <div class="message-body">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. <strong>Pellentesque risus mi</strong>, tempus quis placerat ut, porta nec nulla. Vestibulum rhoncus ac ex sit amet fringilla. Nullam gravida purus diam, et dictum <a>felis venenatis</a> efficitur. Aenean ac <em>eleifend lacus</em>, in mollis lectus. Donec sodales, arcu et sollicitudin porttitor, tortor urna tempor ligula, id porttitor mi magna a neque. Donec dui urna, vehicula et sem eget, facilisis sodales sem.
        </div>
      </article></div>
  </div>
  
  <div class="columns">
    <div class="column is-one-fifth">
        https://bulma.io/documentation/components/card/
        <div class="card">
            <div class="card-image">
              <figure class="image is-4by3">
                <img src="https://bulma.io/images/placeholders/1280x960.png" alt="Placeholder image">
              </figure>
            </div>
            <div class="card-content">
              <div class="media">
                <div class="media-left">
                  <figure class="image is-48x48">
                    <img src="https://bulma.io/images/placeholders/96x96.png" alt="Placeholder image">
                  </figure>
                </div>
                <div class="media-content">
                  <p class="title is-4">John Smith</p>
                  <p class="subtitle is-6">@johnsmith</p>
                </div>
              </div>
          
              <div class="content">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                Phasellus nec iaculis mauris. <a>@bulmaio</a>.
                <a href="#">#css</a> <a href="#">#responsive</a>
                <br>
                <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
              </div>
            </div>
        </div>
    </div>
    <div class="column">
        <div class="dropdown is-hoverable">
            <div class="dropdown-trigger">
              <button class="button" aria-haspopup="true" aria-controls="dropdown-menu4">
                <span>Hover me</span>
                <span class="icon is-small">
                  <i class="fas fa-angle-down" aria-hidden="true"></i>
                </span>
              </button>
            </div>
            <div class="dropdown-menu" id="dropdown-menu4" role="menu">
              <div class="dropdown-content">
                <div class="dropdown-item">
                  <p>You can insert <strong>any type of content</strong> within the dropdown menu.</p>
                </div>
              </div>
            </div>
          </div>
    </div>
    <div class="column">
        <div class="card">
            <header class="card-header">
              <p class="card-header-title">
                Component
              </p>
              <button class="card-header-icon" aria-label="more options">
                <span class="icon">
                  <i class="fas fa-angle-down" aria-hidden="true"></i>
                </span>
              </button>
            </header>
            <div class="card-content">
              <div class="content">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus nec iaculis mauris.
                <a href="#">@bulmaio</a>. <a href="#">#css</a> <a href="#">#responsive</a>
                <br>
                <time datetime="2016-1-1">11:09 PM - 1 Jan 2016</time>
              </div>
            </div>
            <footer class="card-footer">
              <a href="#" class="card-footer-item">Save</a>
              <a href="#" class="card-footer-item">Edit</a>
              <a href="#" class="card-footer-item">Delete</a>
            </footer>
          </div>
    </div>
  </div>
  https://bulma.io/documentation/components/navbar/
  <nav class="navbar" role="navigation" aria-label="main navigation">
  <div class="navbar-brand">
    <a class="navbar-item" href="https://bulma.io">
      <img src="https://bulma.io/images/bulma-logo.png" width="112" height="28">
    </a>

    <a role="button" class="navbar-burger" aria-label="menu" aria-expanded="false" data-target="navbarBasicExample">
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
      <span aria-hidden="true"></span>
    </a>
  </div>

  <div id="navbarBasicExample" class="navbar-menu">
    <div class="navbar-start">
      <a class="navbar-item">
        Home
      </a>

      <a class="navbar-item">
        Documentation
      </a>

      <div class="navbar-item has-dropdown is-hoverable">
        <a class="navbar-link">
          More
        </a>

        <div class="navbar-dropdown">
          <a class="navbar-item">
            About
          </a>
          <a class="navbar-item">
            Jobs
          </a>
          <a class="navbar-item">
            Contact
          </a>
          <hr class="navbar-divider">
          <a class="navbar-item">
            Report an issue
          </a>
        </div>
      </div>
    </div>

    <div class="navbar-end">
      <div class="navbar-item">
        <div class="buttons">
          <a class="button is-primary">
            <strong>Sign up</strong>
          </a>
          <a class="button is-light">
            Log in
          </a>
        </div>
      </div>
    </div>
  </div>
</nav>

<p> Nested :</p>
<div class="columns">
    <div class="column">
      <p class="bd-notification is-info">First column</p>
      <div class="columns is-mobile">
        <div class="column">
          <p class="bd-notification is-info">First nested column</p>
        </div>
        <div class="column">
          <p class="bd-notification is-info">Second nested column</p>
        </div>
      </div>
    </div>
    <div class="column">
      <p class="bd-notification is-danger">Second column</p>
      <div class="columns is-mobile">
        <div class="column is-half">
          <p class="bd-notification is-danger">50%</p>
        </div>
        <div class="column">
          <p class="bd-notification is-danger">Auto</p>
        </div>
        <div class="column">
          <p class="bd-notification is-danger">Auto</p>
        </div>
      </div>
    </div>
  </div>

  Tables: https://bulma.io/documentation/elements/table/
  <table class="table">
    <thead>
      <tr>
        <th><abbr title="Position">Pos</abbr></th>
        <th>Team</th>
        <th><abbr title="Played">Pld</abbr></th>
        <th><abbr title="Won">W</abbr></th>
        <th><abbr title="Drawn">D</abbr></th>
        <th><abbr title="Lost">L</abbr></th>
        <th><abbr title="Goals for">GF</abbr></th>
        <th><abbr title="Goals against">GA</abbr></th>
        <th><abbr title="Goal difference">GD</abbr></th>
        <th><abbr title="Points">Pts</abbr></th>
        <th>Qualification or relegation</th>
      </tr>
    </thead>
    <tfoot>
      <tr>
        <th><abbr title="Position">Pos</abbr></th>
        <th>Team</th>
        <th><abbr title="Played">Pld</abbr></th>
        <th><abbr title="Won">W</abbr></th>
        <th><abbr title="Drawn">D</abbr></th>
        <th><abbr title="Lost">L</abbr></th>
        <th><abbr title="Goals for">GF</abbr></th>
        <th><abbr title="Goals against">GA</abbr></th>
        <th><abbr title="Goal difference">GD</abbr></th>
        <th><abbr title="Points">Pts</abbr></th>
        <th>Qualification or relegation</th>
      </tr>
    </tfoot>
    <tbody>
      <tr>
        <th>1</th>
        <td><a href="https://en.wikipedia.org/wiki/Leicester_City_F.C." title="Leicester City F.C.">Leicester City</a> <strong>(C)</strong>
        </td>
        <td>38</td>
        <td>23</td>
        <td>12</td>
        <td>3</td>
        <td>68</td>
        <td>36</td>
        <td>+32</td>
        <td>81</td>
        <td>Qualification for the <a href="https://en.wikipedia.org/wiki/2016%E2%80%9317_UEFA_Champions_League#Group_stage" title="2016–17 UEFA Champions League">Champions League group stage</a></td>
      </tr>
    </tbody>
  </table>

  https://bulma.io/documentation/components/pagination/
  <nav class="pagination" role="navigation" aria-label="pagination">
    <a class="pagination-previous">Previous</a>
    <a class="pagination-next">Next page</a>
    <ul class="pagination-list">
      <li>
        <a class="pagination-link" aria-label="Goto page 1">1</a>
      </li>
      <li>
        <span class="pagination-ellipsis">&hellip;</span>
      </li>
      <li>
        <a class="pagination-link" aria-label="Goto page 45">45</a>
      </li>
      <li>
        <a class="pagination-link is-current" aria-label="Page 46" aria-current="page">46</a>
      </li>
      <li>
        <a class="pagination-link" aria-label="Goto page 47">47</a>
      </li>
      <li>
        <span class="pagination-ellipsis">&hellip;</span>
      </li>
      <li>
        <a class="pagination-link" aria-label="Goto page 86">86</a>
      </li>
    </ul>
  </nav>

  https://bulma.io/documentation/components/panel/
  <nav class="panel">
    <p class="panel-heading">
      Repositories
    </p>
    <div class="panel-block">
      <p class="control has-icons-left">
        <input class="input" type="text" placeholder="Search">
        <span class="icon is-left">
          <i class="fas fa-search" aria-hidden="true"></i>
        </span>
      </p>
    </div>
    <p class="panel-tabs">
      <a class="is-active">All</a>
      <a>Public</a>
      <a>Private</a>
      <a>Sources</a>
      <a>Forks</a>
    </p>
    <a class="panel-block is-active">
      <span class="panel-icon">
        <i class="fas fa-book" aria-hidden="true"></i>
      </span>
      bulma
    </a>
    <a class="panel-block">
      <span class="panel-icon">
        <i class="fas fa-book" aria-hidden="true"></i>
      </span>
      marksheet
    </a>
    <a class="panel-block">
      <span class="panel-icon">
        <i class="fas fa-book" aria-hidden="true"></i>
      </span>
      minireset.css
    </a>
    <a class="panel-block">
      <span class="panel-icon">
        <i class="fas fa-book" aria-hidden="true"></i>
      </span>
      jgthms.github.io
    </a>
    <a class="panel-block">
      <span class="panel-icon">
        <i class="fas fa-code-branch" aria-hidden="true"></i>
      </span>
      daniellowtw/infboard
    </a>
    <a class="panel-block">
      <span class="panel-icon">
        <i class="fas fa-code-branch" aria-hidden="true"></i>
      </span>
      mojs
    </a>
    <label class="panel-block">
      <input type="checkbox">
      remember me
    </label>
    <div class="panel-block">
      <button class="button is-link is-outlined is-fullwidth">
        Reset all filters
      </button>
    </div>
  </nav>

  https://bulma.io/documentation/components/tabs/
  <div class="tabs">
    <ul>
      <li class="is-active"><a>Pictures</a></li>
      <li><a>Music</a></li>
      <li><a>Videos</a></li>
      <li><a>Documents</a></li>
    </ul>
  </div>

  https://bulma.io/documentation/form/general/
  <div class="field">
    <label class="label">Name</label>
    <div class="control">
      <input class="input" type="text" placeholder="Text input">
    </div>
  </div>
  
  <div class="field">
    <label class="label">Username</label>
    <div class="control has-icons-left has-icons-right">
      <input class="input is-success" type="text" placeholder="Text input" value="bulma">
      <span class="icon is-small is-left">
        <i class="fas fa-user"></i>
      </span>
      <span class="icon is-small is-right">
        <i class="fas fa-check"></i>
      </span>
    </div>
    <p class="help is-success">This username is available</p>
  </div>
  
  <div class="field">
    <label class="label">Email</label>
    <div class="control has-icons-left has-icons-right">
      <input class="input is-danger" type="email" placeholder="Email input" value="hello@">
      <span class="icon is-small is-left">
        <i class="fas fa-envelope"></i>
      </span>
      <span class="icon is-small is-right">
        <i class="fas fa-exclamation-triangle"></i>
      </span>
    </div>
    <p class="help is-danger">This email is invalid</p>
  </div>
  
  <div class="field">
    <label class="label">Subject</label>
    <div class="control">
      <div class="select">
        <select>
          <option>Select dropdown</option>
          <option>With options</option>
        </select>
      </div>
    </div>
  </div>
    <div class="field">
    <label class="label">Message</label>
    <div class="control">
      <textarea class="textarea" placeholder="Textarea"></textarea>
    </div>
  </div>
  
  <div class="field">
    <div class="control">
      <label class="checkbox">
        <input type="checkbox">
        I agree to the <a href="#">terms and conditions</a>
      </label>
    </div>
  </div>
  
  <div class="field">
    <div class="control">
      <label class="radio">
        <input type="radio" name="question">
        Yes
      </label>
      <label class="radio">
        <input type="radio" name="question">
        No
      </label>
    </div>
  </div>
  
  <div class="field is-grouped">
    <div class="control">
      <button class="button is-link">Submit</button>
    </div>
    <div class="control">
      <button class="button is-link is-light">Cancel</button>
    </div>
  </div>

  https://bulma.io/documentation/layout/level/
  <!-- Main container -->
<nav class="level">
    <!-- Left side -->
    <div class="level-left">
      <div class="level-item">
        <p class="subtitle is-5">
          <strong>123</strong> posts
        </p>
      </div>
      <div class="level-item">
        <div class="field has-addons">
          <p class="control">
            <input class="input" type="text" placeholder="Find a post">
          </p>
          <p class="control">
            <button class="button">
              Search
            </button>
          </p>
        </div>
      </div>
    </div>
  
    <!-- Right side -->
    <div class="level-right">
      <p class="level-item"><strong>All</strong></p>
      <p class="level-item"><a>Published</a></p>
      <p class="level-item"><a>Drafts</a></p>
      <p class="level-item"><a>Deleted</a></p>
      <p class="level-item"><a class="button is-success">New</a></p>
    </div>
  </nav>

  https://bulma.io/documentation/layout/media-object/
  <article class="media">
    <figure class="media-left">
      <p class="image is-64x64">
        <img src="https://bulma.io/images/placeholders/128x128.png">
      </p>
    </figure>
    <div class="media-content">
      <div class="content">
        <p>
          <strong>Barbara Middleton</strong>
          <br>
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis porta eros lacus, nec ultricies elit blandit non. Suspendisse pellentesque mauris sit amet dolor blandit rutrum. Nunc in tempus turpis.
          <br>
          <small><a>Like</a> · <a>Reply</a> · 3 hrs</small>
        </p>
      </div>
  
      <article class="media">
        <figure class="media-left">
          <p class="image is-48x48">
            <img src="https://bulma.io/images/placeholders/96x96.png">
          </p>
        </figure>
        <div class="media-content">
          <div class="content">
            <p>
              <strong>Sean Brown</strong>
              <br>
              Donec sollicitudin urna eget eros malesuada sagittis. Pellentesque habitant morbi tristique senectus et netus et malesuada fames ac turpis egestas. Aliquam blandit nisl a nulla sagittis, a lobortis leo feugiat.
              <br>
              <small><a>Like</a> · <a>Reply</a> · 2 hrs</small>
            </p>
          </div>
  
          <article class="media">
            Vivamus quis semper metus, non tincidunt dolor. Vivamus in mi eu lorem cursus ullamcorper sit amet nec massa.
          </article>
  
          <article class="media">
            Morbi vitae diam et purus tincidunt porttitor vel vitae augue. Praesent malesuada metus sed pharetra euismod. Cras tellus odio, tincidunt iaculis diam non, porta aliquet tortor.
          </article>
        </div>
      </article>
  
      <article class="media">
        <figure class="media-left">
          <p class="image is-48x48">
            <img src="https://bulma.io/images/placeholders/96x96.png">
          </p>
        </figure>
        <div class="media-content">
          <div class="content">
            <p>
              <strong>Kayli Eunice </strong>
              <br>
              Sed convallis scelerisque mauris, non pulvinar nunc mattis vel. Maecenas varius felis sit amet magna vestibulum euismod malesuada cursus libero. Vestibulum ante ipsum primis in faucibus orci luctus et ultrices posuere cubilia Curae; Phasellus lacinia non nisl id feugiat.
              <br>
              <small><a>Like</a> · <a>Reply</a> · 2 hrs</small>
            </p>
          </div>
        </div>
      </article>
    </div>
  </article>
  
  <article class="media">
    <figure class="media-left">
      <p class="image is-64x64">
        <img src="https://bulma.io/images/placeholders/128x128.png">
      </p>
    </figure>
    <div class="media-content">
      <div class="field">
        <p class="control">
          <textarea class="textarea" placeholder="Add a comment..."></textarea>
        </p>
      </div>
      <div class="field">
        <p class="control">
          <button class="button">Post comment</button>
        </p>
      </div>
    </div>
  </article>

  https://bulma.io/documentation/layout/hero/
  <section class="hero">
    <div class="hero-body">
      <p class="title">
        Hero title
      </p>
      <p class="subtitle">
        Hero subtitle
      </p>
    </div>
  </section>

  https://bulma.io/documentation/layout/tiles/
  <div class="tile is-ancestor">
    <div class="tile is-vertical is-8">
      <div class="tile">
        <div class="tile is-parent is-vertical">
          <article class="tile is-child notification is-primary">
            <p class="title">Vertical...</p>
            <p class="subtitle">Top tile</p>
          </article>
          <article class="tile is-child notification is-warning">
            <p class="title">...tiles</p>
            <p class="subtitle">Bottom tile</p>
          </article>
        </div>
        <div class="tile is-parent">
          <article class="tile is-child notification is-info">
            <p class="title">Middle tile</p>
            <p class="subtitle">With an image</p>
            <figure class="image is-4by3">
              <img src="https://bulma.io/images/placeholders/640x480.png">
            </figure>
          </article>
        </div>
      </div>
      <div class="tile is-parent">
        <article class="tile is-child notification is-danger">
          <p class="title">Wide tile</p>
          <p class="subtitle">Aligned with the right tile</p>
          <div class="content">
            <!-- Content -->
          </div>
        </article>
      </div>
    </div>
    <div class="tile is-parent">
      <article class="tile is-child notification is-success">
        <div class="content">
          <p class="title">Tall tile</p>
          <p class="subtitle">With even more content</p>
          <div class="content">
            <!-- Content -->
          </div>
        </div>
      </article>
    </div>
  </div>

  