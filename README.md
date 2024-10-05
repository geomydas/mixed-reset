# mixed-reset

## What is this?

It is a combined CSS reset from Andy Bell's CSS reset, Josh Comeau's CSS reset and TailwindCSS' preflight

## Why did I make this?

So that I can better manage my CSS reset and so that I have the best of both worlds of the resets.

## Usage

### Option 1 (NPM)

1. Install mixed-reset using NPM
   ```
   npm install mixed-reset
   ```
2. `<link>` or `@import` the reset inside the HTML or CSS

   ```
   <!-- HTML -->
   <link rel="stylesheet" href="/node_modules/mixed-reset/mixed-reset.min.css" >
   ```

   ```
   /* CSS */
   @import "/node_modules/mixed-reset/mixed-reset.min.css";
   ```

3. Et viola!

### Option 2 (git)

1. Clone this repository by using HTTPS, SSH, or GitHub CLI
   ```
   # HTTPS
   git clone https://github.com/geomydas/mixed-reset.git
   ```
   ```
   # SSH
   git clone git@github.com:geomydas/mixed-reset.git
   ```
   ```
   # GitHub CLI
   gh repo clone geomydas/mixed-reset
   ```
2. Link or import the CSS file inside the folder named `mixed-reset`

   ```
   <!-- HTML -->
   <link rel="stylesheet" href="/mixed-reset/mixed-reset.min.css" >
   ```

   ```
   /* CSS */
   @import "/mixed-reset/mixed-reset.min.css";
   ```

3. Et voila!
