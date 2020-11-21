# Grand Theft Bike V - Courses
 
This repository contains courses for [GT Bike V Mod](https://de.gta5-mods.com/scripts/gt-bike-v). Download **courses** from the [release](https://github.com/gtbikev/courses/releases) page. Looking for a tool to create courses? Visit [route-builder](https://github.com/gtbikev/route-builder) repository.

## Courses

| Course Name              | Type   | Distance      | Elevation   | Author       |
| :----------------------- | :----- | :------------ | :---------- | :----------- |
| Alamo Sea                | Mixed  | 9.9km/6.2mi   | 70m/230ft   | N. Matas     |
| Central 8                | Road   | 11.2km/6.9mi  | 434m/1424ft | M. Urech     |
| Davis Quartz             | Gravel | 3.8km/2.4mi   | 73m/242ft   | M. Urech     |
| Docklands                | Road   | 17.0km/10.5mi | 380m/1246ft | M. Urech     |
| East Los Santos          | Road   | 8.8km/5.5mi   | 280m/918ft  | M. Urech     |
| El Burro Heights         | Gravel | 5.0km/3.1mi   | 92m/301ft   | M. Urech     |
| Foothills                | Mixed  | 37.0km/23.0mi | 678m/2224ft | SK. Yeatts   |
| Full Circle             | Mixed  | 48.2km/30.0mi | 891m/2922ft | SK. Yeatts   |
| Grapeseed                | Gravel | 4.5km/2.8mi   | 44m/145ft   | M. Urech     |
| Gravelfondo              | Gravel | 24.0km/14.9mi | 344m/1128ft | M. Urech     |
| Great Chaparral          | Gravel | 9.8km/6.0mi   | 126m/413ft  | M. Urech     |
| Land Act Dam Loop        | Road   | 5.0km/3.1mi   | 98m/323ft   | R. Slaughter |
| Los Santos Hills         | Road   | 14.0km/8.7mi  | 206m/677ft  | N. Matas     |
| Marlowe Vineyards        | Trail  | 3.8km/2.3mi   | 142m/466ft  | M. Urech     |
| Mount Chilliad           | Trail  | 10.0km/6.2mi  | 278m/912ft  | M. Urech     |
| Mount Josiah             | Gravel | 8.7km/5.4mi   | 90m/295ft   | C. Davi      |
| Mount Josiah & Alamo Sea | Gravel | 16.7km/10.4mi | 141m/463ft  | C. Davi      |
| Palomino Highlands       | Road   | 7.0km/4.3mi   | 123m/404ft  | A. Beck      |
| Redwood Lights           | Gravel | 1.8km/1.1mi   | 32m/105ft   | M. Urech     |
| Richman Golf             | Mixed  | 1.3km/0.8mi   | 17m//56ft   | M. Urech     |
| Route 68                 | Road   | 7.3km/4.5mi   | 228m/748ft  | M. Urech     |
| Santos Rally             | Mixed  | 49.0km/30.5mi | 378m/1242ft | SK. Yeatts   |
| Senora Desert            | Gravel | 8.0km/5.0mi   | 53m/274ft   | M. Urech     |
| Suburb Crit              | Road   | 1.4km/0.9mi   | 64m/210ft   | A. Beck      |
| The Tourist              | Road   | 16.0km/9.9mi  | 345m/1132ft | R. Slaughter |
| Tour Los Santos          | Road   | 30.1km/18.7mi | 533m/1750ft | N. Matas     |
| Vinewood Heights         | Road   | 8.0km/5.0mi   | 202m/661ft  | R. Slaughter |
| Vinewood Racetrack       | Gravel | 1.0km/0.6mi   | 18m/59ft    | M. Mohan     |
| West Coast               | Gravel | 12.1km/7.5mi  | 316m/1036ft | M. Urech     |
| Windy Hills              | Gravel | 9.8km/6.1mi   | 166m/542ft  | M. Urech     |

## Contributing

There are many ways in which you can participate in the project, for example:

* [Download](https://github.com/gtbikev/courses/releases), test ride courses and provide feedback on [github](https://github.com/gtbikev/courses/issues?q=is%3Aissue+is%3Aopen+label%3Averify) or [facebook group](https://www.facebook.com/groups/1089053124812221/)
* [Submit bugs and feature requests](https://github.com/gtbikev/courses/issues), and help verify as they are checked in
* Submit new courses or fixing existing issues

## Guidelines

Enclosed you find some guidelines for contributing.

**Submit new courses**

* You cannot publish a course unless you have permission from the owner/creator
* All courses in this repository are licensed under [Creative Commons Public Domain (CC0) license](https://creativecommons.org/share-your-work/public-domain/cc0/). In order to waive all copyrights and related or neighboring rights, add the following comment with the pull request: *I, {your name} hereby waive all copyright and related or neighboring rights together with all associated claims and causes of action with respect to this work to the extent possible under the law*.
* Course has to be tested against the `latest official release` to ensure a smooth end user experience
* Don't update CHANGELOG, LICENSE or README. These files will be updated once a release will be done
* It's recommended to use GitHub [pull requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) to submit new courses
* Pull request must have the following files commited: course (.json) file, activity (.fit) file
* Pull request must have the following metadata information in the comment: *course name, distance (km/mi), elevation (m/ft), author, description*

**Fixing issues**

* Course has to be tested against the `latest official release` to ensure a smooth end user experience
* Don't update CHANGELOG, LICENSE or README. These files will be updated once a release will be done
* It's recommended to use GitHub [pull requests](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/about-pull-requests) to fix existing issues
* Pull request must have the following files commited: *course (.json) file*, *activity (.fit) file*
* Pull request must have the following metadata information in the comment: *course name, distance (km/mi), elevation (m/ft), author, description*

**Testing courses**

* Use the following testing setup: Auto Drive = `on`, Avoid Obstacles = `on`, SLOPESCALE `0.5`
* Document testing hardware device (generation or year) and installed mods (with version)
* Report issues by specifying waypoint distance and adding waypoint images or videos

> Example:
> 
> **Test Setup**  
> Course: Docklands  
> Wahoo Kickr Core, 2018  
> Mods: GT Bike V (0.4.0.4) 
> 
> **Test Result**  
> Everything works well, but there is an issue with waypoint 6.9km/4.2mi. Rider turns right instead of going straight.

## License

Licensed under the [Creative Commons Public Domain](https://creativecommons.org/share-your-work/public-domain/cc0/) license.
