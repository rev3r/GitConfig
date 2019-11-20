# File location (on Windows)

`%USERPROFILE%\.gitconfig`

# Editing (from git)

`git config --global -e`

# Special characters explanation

<dl>
  <dt><code>!</code></dt>
  <dd>shell mode (allows multiple commands, bash commands etc.)</dd>

  <dt><code>&&</code></dt>
  <dd>continue if current command succeed</dd>

  <dt><code>||</code></dt>
  <dd>continue if current command failed</dd>

  <dt><code>\</code></dt>
  <dd>allow to continue in next line</dd>

  <dt><code>#</code></dt>
  <dd>comment rest of the user input (if inside bash) or comment whole line (if outside bash)</dd>

  <dt><code>$...</code></dt>
  <dd>get variable's value</dd>

  <dt><code>$1</code></dt>
  <dd>get first user-provided argument</dd>

  <dt><code>$(...)</code></dt>
  <dd>execute in-place</dd>

  <dt><code>[[ ... ]]</code></dt>
  <dd>inline 'if' that returns status code</dd>

  <dt><code>${1+abc}</code></dt>
  <dd>evaluates to true if parameter exist ('abc' is just random string)</dd>

  <dt><code>\"...\"</code></dt>
  <dd>allow white spaces, but execute code inside</dd>
</dl>

# Usage warning

Code assumes that your base branch is `develop` (which can be altered in the `parent` alias), and all commits are made on dedicated feature branches.

To add testing before push, alter `test` alias.
