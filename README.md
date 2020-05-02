# gulp-starter
Primary Gulp setup to Kick Start a new Project

Following Node Modules are included in this Gulp Starter Pack
<ul>
<li>gulp-sass</li>
<li>browser-sync</li>
<li>gulp-sass</li>
<li>gulp-useref</li>
<li>gulp-uglify</li>
<li>gulp-if</li>

<li>gulp-clean-css</li>
<li>gulp-cache</li>
<li>del</li>
<li>run-sequence</li>
<li>gulp-autoprefixer</li>
<li>es6-promise</li>
<li>gulp-imagemin</li>

</ul>

No need to run -> npm install command all node modules are already included in starter pack.

# check for updates
-> npm install npm-check-updates -g
In relevent project directory
-> npm-check-updates
# Update all
-> npm-check-updates -u

<h1>Fatal error: watch ENOSPC  FIX</h1>
<p>Run below code if you get watch error. Solution works on Ubuntu 14.04</p>
<code>
echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p
</code>
