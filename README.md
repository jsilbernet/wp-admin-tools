# WP-Admin-Tools

WordPress Admin Tools.
Make it easy to create backups and navigate around.
**This is the Cloudways version.**

## Usage

1. Clone this repo to your server.
2. Adjust the `MAIN_SITE` and `THEME_HOME` variables in `init_session` to reflect the name of your directories.
3. Run `init_session`. (You can also add it to be run when you login.)

----

* To backup your entire main site, just run `wp_backup`.
* You can also navigate around your site easily, e.g. `cd $THEME_HOME`.
* The admin tools come with *WP-CLI* installed, including the command auto-completion.

## Extended usage

* Install *Python* packages in user mode: e.g. `pip install awscli --user`. Packages will be put in the right place / PATH will be set correctly.
* Once *AWS-CLI* is installed you will also have command auto-completion. 
