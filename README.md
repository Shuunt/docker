# aws-demo-php-simple-app
Application was created for use with an AWS Partner blog post and will be used for demonstration purposes for other web applications.

This web application utilizes the PHP scripting language to gather information system information and display that information using HTML/CSS/Chart.js.

Information gathered is a read-only file handler that reads information from /proc/. Information gathered is, CPU load, memory use, network packet types, and disk use. 

Features:
 - Simple PHP application tested on PHP 5.3 - 5.6
 - Load generation utility included

Other Items:
 - Currently no database test capabilities

Miscelaneous Informations:
 - In order to run the pipeline, be carefull to put in priviliged mode to true in your /etc/gitlab-runner/config.toml file.
 - The pipeline use DinD features, you're free to look at it.

Authors:
 - This exam was made by Anthony Drogrez.
 - The initial project and credits belongs to the user aws-samples, feel free to take a look at it on the following url: https://github.com/aws-samples/aws-demo-php-simple-app
 - The corrector of this exam will be Thomas.G, hello sir if you're reading this !
