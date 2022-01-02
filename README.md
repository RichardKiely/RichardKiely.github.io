
<!DOCTYPE html>
<html>
  <head>
    <title>Quality Assurance with Chai | freeCodeCamp.org</title>
    <link rel="shortcut icon" href="https://cdn.freecodecamp.org/universal/favicons/favicon-32x32.png" type="image/x-icon"/>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="style.css">
  </head>
  <body>
    <header>
      <h1>
        Automated Testing
      </h1>
    </header>
    <main>
      <h2>Basic Assertion Tests Example</h2>
      <div class="pane">
      // #1
        <br>
    test('#isNull, #isNotNull', function () { <br>
      assert.isNull(null, 'This is an optional error description - e.g. null is null');<br>
      assert.isNotNull(1, '1 is not null');
    });
      </div>
    </main>
    <script src='/client.js'></script>
  </body>
</html>
