# WPTT Developer Constants

Contributors: Curtis McHale
Tags: wp_mail, email logging
Requires at least: 3.6
Tested up to: 3.7
Stable tag: 1.0


## Description

Basic plugin that allows you to define constants for live/local/staging.

Ideal for hosting like WPEngine which blows out the staging wp-config.php file when you push live->staging with their tools

## Installation

1. Extract to your wp-content/mu-plugins/ folder. Create it if it doesn't exist

2. Plugin is always run and won't show up in the WordPress admin

3. Follow this repository for any updates since MU Plugins don't get update notifications.

## Usage

Use this is the mu-plugins/ folder in your WordPress site. It's meant for you to change the code. Define your live, local, and staging site url's as needed.

You can then use them in any plugin since they are defined before regular plugins are loaded. It lets you do stuff like configure email logging on all staging and local sites by checking the defined constants.

## Changelog

### 1.0

- basic constants configuration
