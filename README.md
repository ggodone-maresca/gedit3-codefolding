gedit3-codefolding
==================

This plugin adds code folding support to gedit 3.x. It supports several (meaning more than 1) languages. Note that this plugin is <b>not</b> compatible with gedit 2.x.

This has not been tested on gedit versions before 3.10. If you're on gedit &lt; 3.10 and the plugin does not work, try changing the loader in /src/codefolding.plugin from "python3" to "python".

##Features
Besides folding indivudual blocks by clicking the respective block start markers on the left margin, two other operations are supported either from the Tools menu or from the keyboard like this
- <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>T</kbd>: Toggle all blocks
- <kbd>Alt</kbd>+<kbd>Shift</kbd>+<kbd>C</kbd>: Fold current block

##Suported languages
- C/C++
- C#
- CSS
- Go
- Graphviz Dot
- HTML
- Java
- Javascript
- JSON
- Lua
- Objective-C
- Perl
- Prolog
- R
- Ruby
- sh
- Scheme
- SQL
- XML

##Installation
Copy the codefolding directory of this repo & place it in your ~/.local/share/gedit/plugins directory.

##Screenshots
Please note that most of the exmaple code in the screenshots are taken from the public domain. I apologize if I am not respecting someone's copyright here.
#####Java
![alt tag](https://raw.github.com/satyajitc/gedit3-codefolding/master/screenshots/Java.png)
#####Javascript
![alt tag](https://raw.github.com/satyajitc/gedit3-codefolding/master/screenshots/JS.png)


##Notes
- Code folding is dependent on properly formatted blocks of code. If the folding behaves erratic try reformatting the code
- A simple way of reformatting to facilitate folding is to have block start and end constructs in seperate individual lines
- A light color scheme works best (actually dark schemes don't show the markers at all) with this plugin, for now

##License
<pre><code>Permission to copy, use, modify, sell and distribute this software is granted. 
This software is provided "as is" without express or implied warranty, and with no claim as to its suitability
for any purpose.
</code></pre>
