ArchivesSpace PUI Help Page Plugin (Customized for Boston Public Library)
======================================

**Special thanks to Randy Kuehn from University of Louisville for writing and sharing this plugin!**
**Special thanks to Yale Univeristy Libary YAMS committee for additions to this plugin**
Forked from Yale University Library and edited for BPL customizations.

This is a plugin that adds a Help page to the ArchivesSpace PUI. 


Enable the plugin
-----------------

Edit `config.rb` and append:

```
AppConfig[:plugins] << "pui-help-bpl"
```
Edit the views/help/index.html.erb file as desired to populate your Help page.

Restart ArchivesSpace.

---
