# Outliars ADA Project: ♟️ The Grandmaster's Path

# Listen, we have been working (Well... AND using [ChatGPT](chat.openai.com)) for a long time waiting for this moment to come, and here it is!

# So buckle on because this is going to be a long ride.


<button name="button" onclick=Page1>CLICK HERE TO START</button>
<!DOCTYPE html>
<html lang="en">
<head>
  <style>
    /* CSS styles here */
  </style>
</head>
<body>
  <button name="button" onclick="Page1()">CLICK HERE TO START</button>
  <script>
    function Page1() {
      alert("Button clicked! Add your functionality here.");
    }
  </script>
</body>
</html>

## Usage
1. Fork (copy) this repository by clicking the "Fork" button on the top right corner.
2. Go to "Settings" -> "Pages" in your forked repository. Under "Branch" change "None" to "master" and click "Save".
3. Edit the `_config.yml` file in your forked repository to change the site title (after `title:`) and description (after `description:`).
4. Build your own page by editing this `README.md` (home page) and creating new `.md` files (other pages), formatting is done with standard [GitHub Markdown syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax), we provide an example file `example.md` in the repository.
**Important**: Please include ```--- layout: default ---``` (the first three line in `example.md`) at the beginning of your every newly created `.md` file.
5. Add your new `.md` files to the site by editing the `_config.yml` file in your forked repository. Under `navigation:` add a new pair of `- title:` and `url:`, and fill their value with your page name and `.md` file name. Remember to remove the `- title:` and `url:` pair for the example page.
6. Go back to "Settings" -> "Pages" to find your website link.
