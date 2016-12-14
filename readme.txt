=== Sched Embed ===
<<<<<<< HEAD
Contributors: sched, codeforthepeople, johnbillion, simonwheatley
Tags: sched, sched.org, sched.com, embed, shortcode
=======
Contributors: cftp, johnbillion, simonwheatley
Tags: sched, sched.org, embed, shortcode
>>>>>>> First version
Requires at least: 3.4
Tested up to: 3.5
Stable tag: trunk
License: GPL v2 or later

Embed event content from sched.org into your WordPress site.

== Description ==

<<<<<<< HEAD
This plugin provides a shortcode which allows you to embed event content from sched.org into your WordPress site.

Due to WordPress security restrictions, Authors and Contributors on your site will be unable to use the standard embed code provided by sched.org. If you use WordPress Multisite then nobody on your site will be able to use the standard embed code at all. This plugin allows you to embed event content from sched.org using a simple shortcode instead.

Embedding event content into your WordPress site requires a paid account on sched.org. [View available plans here.](http://sched.org/plans)


Plugin development was sponsored by [Internet Retailing](http://internetretailing.net).
=======
This plugin allows you to quickly swap between user accounts in WordPress at the click of a button. You'll be instantly logged out and logged in as your desired user. This is handy for test environments where you regularly log out and in between different accounts, or for adminstrators of sites who need to switch between multiple accounts.
>>>>>>> First version

== Installation ==

You can install this plugin directly from your WordPress dashboard:

 1. Go to the *Plugins* menu and click *Add New*.
 2. Search for *Sched Embed*.
 3. Click *Install Now* next to the *Sched Embed* plugin.
 4. Activate the plugin.

Alternatively, see the guide to [Manually Installing Plugins](http://codex.wordpress.org/Managing_Plugins#Manual_Plugin_Installation).

= Usage =

Embed content from your sched.com event by adding the following shortcode to your post or page content:

`[sched url="http://example.sched.com/"]`

<<<<<<< HEAD
Replace `http://example.sched.com/` with the URL of the event page you wish to embed. You can use the URL of any page of your event on sched.com. Simply copy the URL of the page from sched.com and paste it into your shortcode.

=======
`[sched url="example.sched.org"]`

Replace `example.sched.org` with the URL of your own event. By default, the event schedule will be embedded. See the FAQ for how to embed a list of attendees, sponsors, speakers or exhibitors.
>>>>>>> First version

== Frequently Asked Questions ==

= What can I embed with this shortcode? =

<<<<<<< HEAD
You can embed any of your sched.com event pages. Simply copy the URL of the page from sched.com and paste it into your shortcode.
=======
You can embed any of the following views using the `view` attribute:

**Schedule (Default View)**

`[sched url="example.sched.org" view="schedule"]` or just `[sched url="example.sched.org"]`

**Schedule: Expanded**

`[sched url="example.sched.org" view="expanded"]`

**Schedule: Grid**

`[sched url="example.sched.org" view="grid"]`

**Schedule: By Venue**

`[sched url="example.sched.org" view="venues"]`

**Attendees**

`[sched url="example.sched.org" view="attendees"]`

**Speakers**

`[sched url="example.sched.org" view="speakers"]`

**Sponsors**

`[sched url="example.sched.org" view="sponsors"]`

**Exhibitors**

`[sched url="example.sched.org" view="exhibitors"]`
>>>>>>> First version

= Can I specify the width of the embed? =

You can specify the width of the embed using the `width` attribute:

<<<<<<< HEAD
`[sched url="http://example.sched.com/" width="500"]`
=======
`[sched url="example.sched.org" width="500"]`
>>>>>>> First version

Note that sched.com only supports widths of 500, 600, 700, 800 and 900 (pixels). The default width is 990 pixels.

= Can I hide the sidebar in the embed? =

You can hide the sidebar in the embed by setting the `sidebar` attribute to 'no':

<<<<<<< HEAD
`[sched url="http://example.sched.com/" sidebar="no"]`
=======
`[sched url="example.sched.org" sidebar="no"]`
>>>>>>> First version

= Can I improve the colour scheme for use on a dark background colour? =

You can specify a colour scheme which is suitable for use on a dark background by setting the `background` attribute to 'dark':

<<<<<<< HEAD
`[sched url="http://example.sched.com/" background="dark"]`

Note that this does not put a dark background behind the schedule, it simply changes the text colour to be suitable for a dark background if your site has one.
=======
`[sched url="example.sched.org" background="dark"]`
>>>>>>> First version

= Can I specify the fallback text? =

You can specify the fallback text which will be shown to users who have JavaScript disabled:

<<<<<<< HEAD
`[sched url="http://example.sched.com/"]View my event on sched.com[/sched]`
=======
`[sched url="example.sched.org"]View my event on sched.org[/sched]`
>>>>>>> First version

If you don't specify this, the title of the event page will be used.

== Screenshots ==

1. An embedded event schedule

== Upgrade Notice ==

<<<<<<< HEAD
= 1.1 =
* Allow any event page from sched.com to be embedded.

== Changelog ==

= 1.1.3 =
* Made the compiled URL schemaless (//)
* Domain changes (sched.org -> sched.com)
* Allow `[sched.com]` to be used as the shortcode

= 1.1.2 =
* Version bump

= 1.1.1 =
* Sched.com taking over the ownership over plugin.

= 1.1 =
* Allow any event page from sched.com to be embedded.

= 1.0.1 =
* Allow `[sched.org]` to be used as the shortcode in addition to `[sched]`.

=======
= 1.0 =
* Initial release.

== Changelog ==

>>>>>>> First version
= 1.0 =
* Initial release.
