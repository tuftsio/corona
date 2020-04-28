---
---
<html>
  <head>
    <title>{{ title }}</title>
    <style>
    div#content {
      width: 600px;
      margin-left: auto;
      margin-right: auto;
    }
    div section {
      border: solid 1px;
      margin-bottom: 20px;
    }
    div#footer {
      margin-top: 50px;
      font-size: small;
    }
    div#elephant img {
      width: 100px;
      position: fixed;
      right: 0;
      bottom: 0;
    }
    </style>
  </head>
  <body>
    <div id="content">
      {{ content }}
      <div id="footer">
        Have some ideas for this website? Send a
        <a href="https://github.com/tuftsio/corona">pull request</a>! (<a href="http://oss-watch.ac.uk/resources/pullrequest">?</a>)
      </div>
    </div>
    <div id="elephant">
      <img src="jumbo.png" alt="Jumbo on a laptop" />
    </div>
  </body>
</html>
