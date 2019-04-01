# Special characters explanation

<dl>
  <dt><code>!</code></dt>
  <dd>shell mode (allows multiple commands, non-git commands etc.)</dd>

  <dt><code>&&</code></dt>
  <dd>execute next command if current succeed</dd>

  <dt><code>\</code></dt>
  <dd>allow command to continue in newline</dd>

  <dt><code>#</code></dt>
  <dd>comment rest of the user input</dd>

  <dt><code>$...</code></dt>
  <dd>get variable's value</dd>

  <dt><code>$1</code></dt>
  <dd>first user provided argument</dd>

  <dt><code>$(...)</code></dt>
  <dd>execute in-place</dd>

  <dt><code>\"...\"</code></dt>
  <dd>allow white spaces</dd>
</dl>

# File location (on Windows)

`%USERPROFILE%\.gitconfig`

# Usage warning

Code assumes that you have `develop` branch, and all commits are made on dedicated feature branches.
