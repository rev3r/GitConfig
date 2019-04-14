# File location (on Windows)

`%USERPROFILE%\.gitconfig`

# Editing (from git)

`git config --global -e`

# Special characters explanation

<dl>
  <dt><code>!</code></dt>
  <dd>shell mode (allows multiple commands, bash commands etc.)</dd>

  <dt><code>&&</code></dt>
  <dd>continue if current command succeed (or standard 'AND' when inside 'if')</dd>

  <dt><code>||</code></dt>
  <dd>continue if current command failed</dd>

  <dt><code>\</code></dt>
  <dd>allow to continue in next line</dd>

  <dt><code>#</code></dt>
  <dd>comment rest of the user input</dd>

  <dt><code>$...</code></dt>
  <dd>get variable's value</dd>

  <dt><code>$1</code></dt>
  <dd>get first user-provided argument</dd>

  <dt><code>$(...)</code></dt>
  <dd>execute in-place</dd>

  <dt><code>\"...\"</code></dt>
  <dd>allow white spaces</dd>

  <dt><code>[[ ... ]]</code></dt>
  <dd>inline 'if' that returns status code</dd>
</dl>

# Usage warning

Code assumes that your base branch is `develop` (which can be altered in the `parent` alias), and all commits are made on dedicated feature branches.
