<!--
    This source file is part of the open-source project
    ExpressionEngine User Guide (https://github.com/ExpressionEngine/ExpressionEngine-User-Guide)

    @link      https://expressionengine.com/
    @copyright Copyright (c) 2003-2020, Packet Tide, LLC (https://www.packettide.com)
    @license   https://expressionengine.com/license Licensed under Apache License, Version 2.0
-->
# ExpressionEngine v7 Change Log

## Version 7.1.3
(Release: September 1, 2022)

- **Contributors** 🙌
<div class="max-w-7xl mx-autotext-center">
<div class="space-y-8 sm:space-y-12">
    <ul role="list" class="mx-auto grid grid-cols-2 gap-x-4 gap-y-1 sm:grid-cols-4 md:gap-x-6 lg:max-w-5xl lg:gap-x-8 lg:gap-y-1 xl:grid-cols-5">
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/752126?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yuri Salimovskiy</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=intoeetive" target="_BLANK">@intoeetive</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/563996?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Bryan Nielsen</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=bryannielsen" target="_BLANK">@bryannielsen</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/23382425?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yulya Lebed</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=Yulyaswan" target="_BLANK">@Yulyaswan</a></p></div></div></div></li>
    </ul>
</div>
</div>


- **Bug Fixes** 💃🐛
  - Resolved [#2331](https://github.com/ExpressionEngine/ExpressionEngine/issues/2331) where saving template revision was causing SQL error when using long table prefix
  - Resolved [#2335](https://github.com/ExpressionEngine/ExpressionEngine/issues/2335) where having references to non-existing files in File field could case PHP error in Entry Manager listing
  - Resolved [#2116](https://github.com/ExpressionEngine/ExpressionEngine/issues/2116) where disabling MFA globally could cause redirect loop on login for some users
  - Resolved [#2279](https://github.com/ExpressionEngine/ExpressionEngine/issues/2279) where ColorPicker dropdown was not visible in new Grid rows
  - Resolved [#2131](https://github.com/ExpressionEngine/ExpressionEngine/issues/2131), [#913](https://github.com/ExpressionEngine/ExpressionEngine/issues/913) where moving fields between tabs in Channel Layouts did not work well
  - Resolved [#2121](https://github.com/ExpressionEngine/ExpressionEngine/issues/2121) where hitting esc in New Entry slideout modal could case data loss
  - Resolved [#2338](https://github.com/ExpressionEngine/ExpressionEngine/issues/2338) where vertical layout was not fully supported by Grid in Pro Variables
  - Resolved [#2340](https://github.com/ExpressionEngine/ExpressionEngine/issues/2340) where Pro Variables of Grid type could show PHP notice on frontend
  - Resolved issue when files could not be uploaded on certain server configurations

## Version 7.1.2
(Release: August 22, 2022)

- **Contributors** 🙌
<div class="max-w-7xl mx-autotext-center">
<div class="space-y-8 sm:space-y-12">
    <ul role="list" class="mx-auto grid grid-cols-2 gap-x-4 gap-y-1 sm:grid-cols-4 md:gap-x-6 lg:max-w-5xl lg:gap-x-8 lg:gap-y-1 xl:grid-cols-5">
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/752126?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yuri Salimovskiy</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=intoeetive" target="_BLANK">@intoeetive</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/563996?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Bryan Nielsen</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=bryannielsen" target="_BLANK">@bryannielsen</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/17785714?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Jonathan Hardisty</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=jHards" target="_BLANK">@jHards</a></p></div></div></div></li>
    </ul>
</div>
</div>

- **Enhancements** 🚀
  - Added support for `form_class` parameter in legacy Forgot Password Form

- **Bug Fixes** 💃🐛
  - Resolved issue when member role record was not deleted after deleting member
  - Resolved issue when URLs to files with special characters in name were not properly encoded
  - Resolved [#2126](https://github.com/ExpressionEngine/ExpressionEngine/issues/2126) where "add field" button was present for field groups that are not saved yet
  - Resolved [#2076](https://github.com/ExpressionEngine/ExpressionEngine/issues/2076), [#2141](https://github.com/ExpressionEngine/ExpressionEngine/issues/2141) where button to update template routes was missing some functionality
  - Resolved [#1901](https://github.com/ExpressionEngine/ExpressionEngine/issues/1901) where add-ons with related models were not properly uninstalled
  - Resolved [#2109](https://github.com/ExpressionEngine/ExpressionEngine/issues/2109) where loading third-party dashboard widgets could cause PHP error
  - Resolved [#2255](https://github.com/ExpressionEngine/ExpressionEngine/issues/2255) where "Anonymize Consent Logs" feature was not fully functional
  - Resolved [#2297](https://github.com/ExpressionEngine/ExpressionEngine/issues/2297) where deferring relationship field was not working for fields with data
  - Resolved [#2279](https://github.com/ExpressionEngine/ExpressionEngine/issues/2279) where ColorPicker field did not display saved values


## Version 7.1.1
(Release: August 19, 2022)

- **Bug Fixes** 💃🐛
  - Resolved issue where license check could return incorrect results
  - Resolved [#2263](https://github.com/ExpressionEngine/ExpressionEngine/issues/2208) where the instructions for adding IP to Blocked list were not correct
  - Minor UI updates

## Version 7.1.0
(Release: August 18, 2022)

- **Contributors** 🙌
<div class="max-w-7xl mx-autotext-center">
<div class="space-y-8 sm:space-y-12">
    <ul role="list" class="mx-auto grid grid-cols-2 gap-x-4 gap-y-1 sm:grid-cols-4 md:gap-x-6 lg:max-w-5xl lg:gap-x-8 lg:gap-y-1 xl:grid-cols-5">
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/13821249?v=4"><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Gavin * JCOGS</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=jcogs-design" target="_BLANK">@jcogs-design</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/53965?v=4"><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Brian Litzinger</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=litzinger" target="_BLANK">@litzinger</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/35812875?v=4"><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Gilbert</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=gilbert-hop" target="_BLANK">@gilbert-hop</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/931642?v=4"><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Sobral</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=robsonsobral" target="_BLANK">@robsonsobral</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/14606?v=4"><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Daniel Jalkut</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=danielpunkass" target="_BLANK">@danielpunkass</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/194579?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Andy Johnson</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=ajohnson" target="_BLANK">@ajohnson</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/11818941?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Matt Johnson</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=matthewjohns0n" target="_BLANK">@matthewjohns0n</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/23382425?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yulya Lebed</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=Yulyaswan" target="_BLANK">@Yulyaswan</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/752126?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yuri Salimovskiy</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=intoeetive" target="_BLANK">@intoeetive</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/1181219?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">robinsowell</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=robinsowell" target="_BLANK">@robinsowell</a></p></div></div></div></li>
    </ul>
</div>
</div>


- **Enhancements** 🚀
  - Added Structure as first-party add-on, shipped with ExpressionEngine
  - Added indicator to display number of installed add-ons, [#1944](https://github.com/ExpressionEngine/ExpressionEngine/issues/1944)
  - Added `edit_date` column in Entry Manager, [#1850](https://github.com/ExpressionEngine/ExpressionEngine/issues/1850)
  - Added possibility to defer initialization of Relationship field
  - Added support for table alias in SQL joins when using Active Record, [#2096](https://github.com/ExpressionEngine/ExpressionEngine/issues/2096)
  - Enable `exp:search:total_results` to be parsed as tag pair, [#1193](https://github.com/ExpressionEngine/ExpressionEngine/issues/1193)
  - Added `has_children` variable to category tags, [#1726](https://github.com/ExpressionEngine/ExpressionEngine/issues/1726)
  - Various UI improvements

- **Bug Fixes** 💃🐛
  - Resolved [#1561](https://github.com/ExpressionEngine/ExpressionEngine/issues/1561) where file column in file grid field was not searchable
  - Resolved issue when PHP error was shown for non-existing addons
  - Resolved [#2157](https://github.com/ExpressionEngine/ExpressionEngine/issues/2157) where Color Picker field was cut off when used inside Grid field
  - Resolved [#2279](https://github.com/ExpressionEngine/ExpressionEngine/issues/2279) where ColorPicker fields were not initialized on page load
  - Resolved [#2115](https://github.com/ExpressionEngine/ExpressionEngine/issues/2115) where conditional validation did not work properly on existing objects
  - Resolved [#2136](https://github.com/ExpressionEngine/ExpressionEngine/issues/2136) where formatters for duration field set to hours type were not parsed properly
  - Resolved [#2105](https://github.com/ExpressionEngine/ExpressionEngine/issues/2105) where adding new row for File Grid inside Fluid could cause validation error
  - Resolved issue where PHP notice could be shown when calling Template library from an add-on
  - Resolved [#2127](https://github.com/ExpressionEngine/ExpressionEngine/issues/2117) where there was a typo in definition of Extension model
  - Resolved [#2248](https://github.com/ExpressionEngine/ExpressionEngine/issues/2248) where emphasized markdown was placed in separate line inside Notes field
  - Resolved [#2103](https://github.com/ExpressionEngine/ExpressionEngine/issues/2103) where value column of conditional field settings could be populated with wrong values
  - Resolved [#2228](https://github.com/ExpressionEngine/ExpressionEngine/issues/2228) where dropdown to create entry inside Relationship field was not positioned properly
  - Resolved [#2063](https://github.com/ExpressionEngine/ExpressionEngine/issues/2063) where outdated resources could be served
  - Resolved issue where MetaWeblog could not post if channel_id is not available
  - Resolved [#1358](https://github.com/ExpressionEngine/ExpressionEngine/issues/1358) where setting CP Homepage for member could cause PHP error on large sites using MSM
  - Resolved issue when sometimes avatar could not be uploaded on frontend

- **Developers** 💻
  - Added extension hook to be executed upon cache clearing, [#1762](https://github.com/ExpressionEngine/ExpressionEngine/issues/1762)

## Version 7.0.3
(Release: August 8, 2022)

- **Contributors** 🙌
<div class="max-w-7xl mx-autotext-center">
<div class="space-y-8 sm:space-y-12">
    <ul role="list" class="mx-auto grid grid-cols-2 gap-x-4 gap-y-1 sm:grid-cols-4 md:gap-x-6 lg:max-w-5xl lg:gap-x-8 lg:gap-y-1 xl:grid-cols-5">
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/11818941?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Matt Johnson</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=matthewjohns0n" target="_BLANK">@matthewjohns0n</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/752126?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yuri Salimovskiy</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=intoeetive" target="_BLANK">@intoeetive</a></p></div></div></div></li>
    </ul>
</div>
</div>

- **Bug Fixes** 💃🐛
  - Fixed issue where Update File Usage utility was not always giving correct results.
  - Resolved issue where files in subfolder were not stored properly in RTE field using Redactor.
  - Resolved [#2208](https://github.com/ExpressionEngine/ExpressionEngine/issues/2208) where language files for some add-ons were not placed in correct location.
  - Resolved issue where Grid inside Fluid was not empty initially
  - Resolved issue where filtering by member group in channel form could result in SQL error

## Version 7.0.2
(Release: August 4, 2022)

- **Contributors** 🙌
<div class="max-w-7xl mx-autotext-center">
<div class="space-y-8 sm:space-y-12">
    <ul role="list" class="mx-auto grid grid-cols-2 gap-x-4 gap-y-1 sm:grid-cols-4 md:gap-x-6 lg:max-w-5xl lg:gap-x-8 lg:gap-y-1 xl:grid-cols-5">
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/563996?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Bryan Nielsen</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=bryannielsen" target="_BLANK">@bryannielsen</a></p></div></div></div></li>
    </ul>
</div>
</div>

- Temporarily disabled Update File Usage utility due to a bug that affected some users. Utility will be re-enabled in 7.0.3

- **Bug Fixes** 💃🐛
  - Fixed issue with file usage stats.

## Version 7.0.1
(Release: August 4, 2022)

- **Contributors** 🙌
<div class="max-w-7xl mx-autotext-center">
<div class="space-y-8 sm:space-y-12">
    <ul role="list" class="mx-auto grid grid-cols-2 gap-x-4 gap-y-1 sm:grid-cols-4 md:gap-x-6 lg:max-w-5xl lg:gap-x-8 lg:gap-y-1 xl:grid-cols-5">
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/55093827?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Andy McCormick</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=ops-andy" target="_BLANK">@ops-andy</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/563996?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Bryan Nielsen</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=bryannielsen" target="_BLANK">@bryannielsen</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/11818941?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Matt Johnson</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=matthewjohns0n" target="_BLANK">@matthewjohns0n</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/23382425?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yulya Lebed</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=Yulyaswan" target="_BLANK">@Yulyaswan</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/752126?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yuri Salimovskiy</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=intoeetive" target="_BLANK">@intoeetive</a></p></div></div></div></li>
    </ul>
</div>
</div>

- **Bug Fixes** 💃🐛
  - Resolved issue where Update File Usage utility did not provide correct results when run for second time.
  - Resolved issue where URLs to files in subfolder were not parsed in {exp:file:entries} tag.
  - Resolved issue where Pro Variables and Pro Search could not be installed on some PHP versions.


## Version 7.0.0
(Release: August 3, 2022)

NOTE:**Note:** If multiple members are needed, an ExpressionEngine Pro license is now required.

- **Contributors** 🙌
<div class="max-w-7xl mx-autotext-center">
<div class="space-y-8 sm:space-y-12">
    <ul role="list" class="mx-auto grid grid-cols-2 gap-x-4 gap-y-1 sm:grid-cols-4 md:gap-x-6 lg:max-w-5xl lg:gap-x-8 lg:gap-y-1 xl:grid-cols-5">
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/194579?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Andy Johnson</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=ajohnson" target="_BLANK">@ajohnson</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/55093827?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Andy McCormick</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=ops-andy" target="_BLANK">@ops-andy</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/563996?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Bryan Nielsen</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=bryannielsen" target="_BLANK">@bryannielsen</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/11818941?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Matt Johnson</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=matthewjohns0n" target="_BLANK">@matthewjohns0n</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/422821?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">TomJaeger</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=TomJaeger" target="_BLANK">@TomJaeger</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/23382425?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yulya Lebed</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=Yulyaswan" target="_BLANK">@Yulyaswan</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/752126?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">Yuri Salimovskiy</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=intoeetive" target="_BLANK">@intoeetive</a></p></div></div></div></li>
<li><div class="space-y-4 text-center"><img class="mx-auto h-20 w-20 rounded-full lg:w-24 lg:h-24" src="https://avatars.githubusercontent.com/u/1181219?v=4" /><div class="space-y-2"><div class="text-xs font-medium lg:text-sm"><p class="mb-1">robinsowell</p><p class="text-indigo-600"><a href="https://github.com/ExpressionEngine/ExpressionEngine/commits?author=robinsowell" target="_BLANK">@robinsowell</a></p></div></div></div></li>
    </ul>
</div>
</div>

- **New File Manager** 🗃️
  - New File Manager design including the additions to [Filters](/control-panel/file-manager/file-manager.md#filters) and [Views](/control-panel/file-manager/file-manager.md#view-options)
  - Added utility action menu to files in the File Manager, allowing for quicker actions to be taken on individual files
  - Added Pop-up preview to thumbnails when viewing files in list view
  - Ability to upload files with drag and drop.
  - Bulk upload files using drag and drop or standard file sytem upload
  - Ability to organize content into [subfolders](/control-panel/file-manager/subfolders.md)
  - Folders can now be created directly on the filesystem through the File Manager
  - Implemented [FlySystem PHP library](https://flysystem.thephpleague.com/docs/) to add more extensiblity to the File Manager.
  - Added support for cloud based file storage through [Adapters](/control-panel/file-manager/adapters.md)
  - Changed how files are referenced in the database. Previously files were referenced using `{filedir_X}filename.ext`. Files are now referenced using `{file:XX:url}`. [Compatiblity Mode](/control-panel/file-manager/file-manager.md#compatibility-mode) is recommended for upgrades until there is confirmation that all add-ons will work with new file data format.
  - File usage is now available in the File Manager to display where a file is used throughout the Control Panel as well as notify users if a file is in use before deleting the file

- **Enhancements** 🚀
  - Added [Front-End Content Management](/advanced-usage/front-end/overview.md) (including Front-End Editing, the Dock, and Prolets)
  - Added [Multi-Factor Authentication](/member/mfa.md)
  - Added Cookie Management and template tags
  - Added [Entry Cloning](/channels/entry_cloning.md)
  - Added the ability to create [Custom Dashboard Widgets](/control-panel/dashboard_management.md#dashboard-management)
  - Added the ability to upload a [Logo and Favicon](/control-panel/settings/branding.md) for the Control Panel.
  - Added Pro Search (formerly Low Search)
  - Added Pro Variables (form Low Variables)
  - Major Performance enhancements across the Control Panel and Front-End

  

- **Design** 🎨
  - Added new light theme. ExpressionEngine 6 theme is still available as the "slate" theme using the Jump Menu
  - Added the option to display Grid fields vertically
  - Added the ability to position Entry Editor fields side-by-side using Publish Layouts
  - Made the secondary sidebar collapsable throughout the Control Panel



- **Bug Fixes** 💃🐛

- **Developers** 💻
  - Forum Add-on has now been removed from ExpressionEngine and made a downloadable add-on from the ExpressionEngine Store. On upgrades which use the Forum Add-on, the add-on will be moved from the `ee/addons` folder to `user/addons` and considered a user installed add-on.
  - Simple Commerce Add-on has now been removed from ExpressionEngine and made a downloadable add-on from the ExpressionEngine Store. On upgrades which use the Simple Commerce Add-on, the add-on will be moved from the `ee/addons` folder to `user/addons` and considered a user installed add-on.
  - Ip to Nation Add-on has now been removed from ExpressionEngine and made a downloadable add-on from the ExpressionEngine Store. On upgrades which use the Ip to Nation Add-on, the add-on will be moved from the `ee/addons` folder to `user/addons` and considered a user installed add-on.
  - The included version of jQuery used in the Control Panel has been updated to v3.6.0
  - Added the option to [globablly cache](/channels/entries.html#cache-refresh-cache_prefix) Channel Entries tag results
  - Added [ENV File Support](/advanced-usage/env-support.md)
  - Added new Shared Form View 
