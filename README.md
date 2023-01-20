# *Add to the darwin.libraries.yml*

gt-alerts:<br>
version: "1.0.x"<br />
css:<br />
theme:<br />
templates/block/custom/alerts/css/gt-alerts.css: {}<br>
js:<br />
dependencies:<br />
- core/jquery<br />

# *Add to the repositories section in composer.json*

"repositories": [<br />
{ <br />
"type": "vcs", <br />
"url": "https://github.gatech.edu/ICWebTeam/block_alerts.git" <br />
}
# *Add to the require in composer.json*

"require": { <br />
"gt/alerts": "dev-master" <br />
},

# *Add to the installer paths in composer.json*
"installer-paths": { <br />
"web/themes/contrib/darwin/templates/block/custom/{$name}": [ <br />
"gt/alerts" <br />
] <br />
},

# **DATABASE SET UP**


![](images/set-up.png)

KEYS:
primary|primary
secondary|secondary
success|success
danger|danger
warning|warning
info|info
light|light
dark|dark
