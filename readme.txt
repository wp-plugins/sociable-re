=== Sociable RE ===
Contributors: jackyfox
Donate link: https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=NRYHZVJNPGGA6
Tags: social, bookmark, bookmarks, bookmarking, social bookmarking, social bookmarks, blogplay
Requires at least: 2.8
Tested up to: 3.0.4
Stable tag: 3.5.2.9

Добавляет кнопки для публикации ссылок в соц. сетях на страницы блога.

== Description ==

Плагин добавляет множество кнопок для публикации ссылок на страницы вашего блога в различных социальных сетях и сервисах закладок.

В русской версии плагина добавлены:

* ВКонтакте
* Мой Мир @mail.ru
* Яндекс.Закладки
* БобрДобр
* Memori.ru
* МоёМесто.ru
* Сто закладок
* MisterWong.RU
* Google Buzz, он же «Живая лента Google»
* Google Orkut
* Live Journal, он же Живой Журнал
* Blogger
* Одноклассники
* Блог Я.ру
* Блог liveinternet.ru

Чего-то не хватает? Запросите добавление Вашего любимого сайта на [странице плагина](http://www.jackyfox.com/sociable-re/)

== Screenshots ==

1. Часть страницы настроек. Порядок кнопок можно задать перетаскиванием
2. Sociable RE в действии.

== Changelog ==
= 3.5.2.9 =
* [add] добавлена кнопка для Я.ру;
* [add] добавлена кнопка для Li.ру;

= 3.5.2.8 =
* [upd] новая иконка для twitter'a;
* [upd] новая иконка для digg'a;
* [add] добавлена кнопка для Blogger;
* [add] добавлена кнопка для Одноклассников;
* [fix] исправлен баг со знаком вопроса в конце заголовка статьи при открытии в IFrame

= 3.5.2.7 =
* Починил ссылку на Google Buzz (Живую ленту). Спасибо за конструктивную критику тов. qnub

= 3.5.2.6 =
* ЖЖ не хочет нормально грузить визуальный редактор в thickbox во всех браузерах, кроме Google Chrome. Поэтому начальная часть поста, передаваемая в ЖЖ, не отображается. Пришлось отключить thickbox для ЖЖ

= 3.5.2.5 =
* Добавлен Живой Журнал
* Исправлены надписи под кнопками закладок Google и Google Buzz

= 3.5.2.4 =
* Добавлена социальная сеть Orkut

= 3.5.2.3 =
* Исправлена ошибка при работе с MisterWong.ru

= 3.5.2.2 = 
* Добавлен Google Buzz (Живая лента)

= 3.5.2.1 = 
* Добавлены сайты: ВКонтакте, Мой Мир @mail.ru, Яндекс.Закладки, БобрДобр, Memori.ru, МоёМесто.ru, Сто закладок, MisterWong.RU
* Страница параметров на русской языке

= 3.5.2 = 
* Added new services MOB, 豆瓣, 豆瓣九点, QQ书签, LaTafanera, SheToldMe, viadeo FR, Diggita, Design Float
* Removed ID properties from sociable anchor tags (share links) 
* FIXED: Having a custom image directory now disables sprite usage, and the icons of services are displayed on sociable configuration page.

= 3.5.1 =
* Fixed the xhtml validation issues
* 'target=blank' (open link in new window) issue solved
* Sprites can now be disabled, allowing for custom icons
* Sprites have been disabled for RSS
* You can now deactivate the blogplay widget from your wordpress dashboard

= 3.5.0 =
* The icons now load in a CSS Sprites, allowing for faster download times.
* These services have been discontinued: BlogMeme FR, BlogMeme SP, co.mments, DesignFloat.com, PPNow.net, Symbaloo.com.
* You can now add links to your browser favorites.
* iFrames added for services that support them.
* You can know unselect the transparency effect on the sociable icons.

= 3.4.4 =
* Another fix for the sociableoff dilemma's, no backwards compatibility unfortunately, so disable sociable again on pages where you want to disable it.

= 3.4.3 =
* Fixed the bug mentioned [here](http://wordpress.org/support/topic/288487) and [here](http://wordpress.org/support/topic/290753) that made it impossible to disable Sociable on a per post/page basis (for real, now).

= 3.4.2 =
* Added a site specific id to each links anchor tag.
* Fixed the bug mentioned [here](http://wordpress.org/support/topic/288487) and [here](http://wordpress.org/support/topic/290753) that made it impossible to disable Sociable on a per post/page basis. 
* "Reintroduced" TwitThis as Twitter.

= 3.4.1 =
* Fixed the Sphinn submit link.

= 3.4 =
* Added the option to add a site to Sociable through a filter, read [How to add a site to Sociable](http://yoast.com/add-sites-to-sociable/).

= 3.3.8 =
* Fixed the option to disable Sociable on a per post / page basis.

= 3.3.7 =
* More bugfixery.

= 3.3.6 =
* Reverted plugin URL fix because of too many people on old WordPress installations complaining. (Upgrade, people, upgrade!)
* Added PHPDoc throughout the plugins code.

= 3.3.5 =
* Added a Hyves button.
* Fixed MSN Reporter button.

= 3.3.4 =
* Fixed RSS.

= 3.3.3 =
* Brought back Tumblr
* Updated PDF link
* Added Posterous
* Smushed all images using [Smush.it](http://smush.it/), reducing the total image file size with 31.72 KB (42.03%)!
* Removed pre - 2.6 compatibility code

= 3.3.1 =
* Added new option to use pure text links, instead of image links.
* Fixed small issue with using target=blank links and the new awe.sm options.
* Allowed for usage without an awe.sm API key, as awe.sm falls back to "default" awe.sm shortlinks.
* Code cleanup for more efficiency in the backend on saving options.
* General code cleanup.
* Moved to the new default Changelog markup.

= 3.3 =
* Added awe.sm integration and some sites.

= 3.2.3 =
* Removed the last bit of non jQuery javascript.
* Improved styling and visual feedback when selecting a site.

= 3.2.2 = 
* Moved style loading to admin_print_styles and scripts to admin_print_scripts.

= 3.2.1 =
* Fixed a bug with printing styles in 2.8 beta.

= 3.2 =
This is a MAJOR update to Sociable. Major Thanks to Jean-Paul of [iPhoneclub](http://www.iphoneclub.nl/) for all his work in looking up all the sites. The full list of changes:

* Restored sociable-admin.js, as it got accidentally removed.
* Added `class="sociablefirst"` to the first site in the list and `class="sociablelast"` to the last one.
* Added:
	* An RSS button, which links to your sites RSS feed
	* Printfriendly.com for both printing and creating a PDF, replacing the original "Print" function, which didn't work from RSS
	* Current
	* FriendFeed
	* MSN Reporter.nl 
	* FS Daily
	* Hello TXT
* Removed the following sites that were no longer working or active:
	* BlinkBits
	* Blogmemes.cn, .net, .jp
	* Blogsvine
	* Book.mark.hu
	* Bumpzee
	* Del.irio.us
	* Feed Me Links
	* Furl (replaced by Diigo)
	* GeenRedactie
	* Kick.ie
	* Leonaut
	* Magnolia
	* Plug IM
	* Pownce
	* Salesmarks
	* Scuttle
	* Shadows
	* Smarking
	* Spurl
	* Taggly
	* Tailrank
	* Tumblr (due to the change to a POST API, which we, unfortunately, can't support with Sociable)
* Updated the following sites to include the excerpt when submitting:
	* Connotea
	* Delicious
	* Digg
	* Ekudos
	* Google Bookmarks
	* NuJij
	* Ping.fm
* Otherwise updated:
	* Google Bookmarks (new icon)
	* Fleck (New URL)
	* Rec6 (new URL)

= 3.1.1 =
* Fixed bug with stylesheet introduced in 3.1.

= 3.1 =
* Converted all images to PNG.
* Cleaned up usage of javascript in the backend and switched to the jquery library that comes with WordPress.
* Allowed for usage of an external image directory.
* Removed pre 2.6 compatibility fixes.

= 3.0.6 = 
* Fixed xhtml bug in Netvibes integration.
* Added Bitacoras.

= 3.0.5 = 
* Added Identi.ca.
* Fixed a bug in Yoast Posts widget.

= 3.0.4 =
* Added Netvibes.

= 3.0.3 =
* Security enhancements, thx to Mark Jaquith.

= 3.0.2 =
* Fixed CSS bug introduced in 3.0.

= 3.0.1 =
* Removed some other, now obsolete, code, reducing the code size by another 4KB.

= 3.0 =
* Fixed IE bug in admin. 
* Cleaned up Admin Area and changed support messages. 
* Removed directory checking for all images (speeds up incredibly). 
* Made display: inline !important to prevent vertical icon display. 
* Updated Wykop icon.

= 2.9.15 =
* Added a fallback for strip_shortcodes to maintain backwards compatibility with WordPress 2.3 and below.

= 2.9.14 =
* Made sure there are no tags or shortcodes in the excerpt.
* Added ping.fm.
* Removed indiagram (shut down).

= 2.9.13 =
* Changed Facebook link from sharer.php (meant for a popup window) to share.php (which has the actual menu on it etc.).

= 2.9.12 =
* Added Tip'd.

= 2.9.11 =
* Added settings link and Ozh admin menu icon.

= 2.9.10 =
* Fixes issue with excerpt not being urlencoded.

= 2.9.9 =
* Fixes for custom fields issues.

= 2.9.8 =
* Fixes for WP 2.7.

= 2.9.6 =
* Added Symbaloo and Tumblr.

= 2.9.5 = 
* Fixed Fark & Propeller links.
* Added missing i18n strings.
* Added Yahoo Buzz.

= 2.9.4 =
* Removed PopCurrent and Rawsugar as they no longer exist.
* Renamed BlueDot to Faves.

= 2.9.3 =
* Added Leonaut & MySpace.
* Fixed plugin description.
* Added option to disable Sociable on a per post basis.
* Added option to display sociable on tag pages.
* Added extra security to config page.
* Fixed print button.
* Fixed Twitter functionality.

= 2.9.2 =
* Added Swedish and Chinese localisations, thx to [Mikael Jorhult](http://www.mishkin.se/) and [Hugo Chen](http://take-ez.com/).

= 2.9.1 =
* Fixed bug where jQuery UI would be loaded twice.

= 2.9 = 
* Removed Tool-Man in favor of jQuery, thx to Martin Joosse.

= 2.8.4 =
* General bugfixes.

= 2.8.3 = 
* Added wikio.it, upnews.it, muti.co.za.
* Made LinkedIn work even better.
* Made opening in a new window optional.

= 2.8.2 = 
* Now adds icons to feeds with excerpts too. 
* Added LinkedIn.

= 2.8.1 =
* Fixed some small issues.
* Made sure tagline shows up again.

= 2.8 =
* Added option to show bookmark icons in feed.
* Added Ratimarks.
* Fixed xhtml compliance.
* Fixed blue dot bug.

= 2.6.9 =
* Fixed WP 2.6 compatibility.

= 2.6.8 =
* Updated inline documentation.

= 2.6.7 =
* Renamed Sk*rt to Kirtsy.
* Added designfloat.
* Fixed description.

= 2.5.4 =
* Added HealthRanker, N4G, Meneame, BarraPunto, Laaik.it and E-mail option.

= 2.5.3 =
* Added Global Grind, Salesmarks, Webnews.de, Xerpi, Yigg.

= 2.5.2 =
* Added NuJIJ, eKudos, Sk-rt, Socialogs and MisterWong.de.

= 2.5.1 =
* Swapped Netscape for Propeller.

Special thanks to [Robert Harm](http://www.die-truppe.com/) for coming up with loads of nice ideas.

== Installation ==

= Обновление =

1. Деактивируйте старый плагин **Sociable**
2. Удалите каталог `../wp-content/plugins/sociable`
3. Распакуйие содержимое архива с последней версией плагина в каталог `../wp-content/plugins/`

= Установка =

1. Скачайте последнюю версию плагина
2. Распакуйие содержимое архива в каталог `../wp-content/plugins/`

= Активация =

1. В контрольной панели WordPress перейдите в раздел **Плагины**
2. Нажмите на кнопку **Активировать** рядом с плагином **Sociable RE**

Полную информацию по плагину ищите на [Sociable RE](http://www.jackyfox.com/sociable-re/).

== Upgrade Notice ==
= 3.5.2.9 =
Добавлены кнопки Я.ру и Ли.ру

= 3.5.2.8 =
Приведен в актуальное состояние внешний вид кнопок твиттера и дигга. Добавлены кнопки для Blogger и Одноклассников. Устранен баг со знаком вопроса

= 3.5.2.7 =
Обязательно обновитесь, чтобы публикация в Google Buzz нормально заработала

= 3.5.2.6 =
Если ваши пользователи испытывают проблемы при работе плагина с Живым Журналом, обновитесь.

= 3.5.2.5 =
Исправлена ошибка в надписях над кнопками закладок Google и Google Buzz
Добавлена кнопка для Живого Журнала

= 3.5.2.4 =
Если вам хочется дать пользователям возможность делиться ссылками в соц.сети Оркут, придется обновиться

= 3.5.2.3 =
Обновитесь, чтобы устранить проблему с добавлением ссылок в MisterWong.ru

= 3.5.2.2 = 
Появилась возможность публиковать ссылки в Google Buzz (Живую ленту)

= 3.5.2.1 = 
Первый релиз русскоязычной версии

== Frequently Asked Questions ==
Ответы на часто задаваемые вопросы вы можете найти на [странице плагина](http://www.jackyfox.com/sociable-re/)
