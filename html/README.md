# html exercises

In this exercises you will have to complete the missing html or remark what should we include. For example:

What is wrong with this HTML?

```html
<customtag>lorem ipsum dolor</customtab>
```

Answer: It is using a key that does not exists.

## Exercise 1

Add what is missing in our html `<head>` tag.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8">
    <title>Document</title>
  </head>
</html>
```

## Exercise 2

This html is not semantic what could we do to improve it.

```html
<body class="main">
  <section class="section">
    <ul>
      <li class="list-item">List item</li>
      <li class="list-item">List item</li>
      <li class="list-item">List item</li>
      <li class="list-item">List item</li>
    </ul>
  </section>
  <section class="section">
    <form class="form">
      <label>description</label>
      <input type="text">
    </form>
  </section>
</body>


## Exercise 3

If we want to include two CSS files like `reset.css`, `main.css`, and one javascript file `app.js`. Where should we include it in this html?

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <script>src="main.css"</script>
  <script>src="reset.css"</script>
  <script>src="app.js"</script>
</head>
<body>

</body>
</html>
```

## Exercise 4

We need to improve this html form markup. This form will call and endpoint `/register` with the right method. We also have to include the correct input type and mark all fields as required.

```html
<form>
  <div>
    <label>name</label>
    <input type="name">
  </div>
  <div>
    <label>surname</label>
    <input type="surname">
  </div>
  <div>
    <label>phone</label>
    <input type="phone">
  </div>
  <div>
    <label>email</label>
    <input type="email">
  </div>
  <div>
    <label>password</label>
    <input type="password">
  </div>
  <input value="register">
</form>
```
