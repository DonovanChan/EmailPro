# EmailPro

Email module for FileMaker Pro

## Overview

FileMaker’s Send Mail script step allows you to send plain text emails through SMTP or the user’s mail client. You need to look beyond native functionalities if you’d like to use HTML formatting or send multiple attachments. HTML-formatted emails in particular can provide some fantastic polish to your solutions.

There are some great email plug-ins out there, but sometimes I don’t think my needs justify the cost. This module handles the following scenarios free of cost:

- HTML-formatted content
- Multiple attachments
- SMTP authenticate over SSL/TLS
- Multiple To, CC and/or BCC recipients
- Custom From and Reply-To headers
- Server-side compatible

## Usage

Just call the “. emailPro . send” script. It takes its parameters in [Let format](http://www.modularfilemaker.org/documentation/#Passing_Parameters). If you prefer to use a different parameter format, please see the [ParamConverter](http://www.modularfilemaker.org/2013/11/paramconverter/) module for an easy bridge between formats.

See the README script for more information on testing and customizing your implementation.

## Requirements

- [bBox plug-in](http://www.beezwax.net/bbox) (Free)
- Mac OS clients only! (Sorry. bBox is only compatible with OS X. Let me know if you’d like to talk about adding compatibility for some other plug-in.)
Installation

Just find a place to store the plug-in file in your solution, import the module scripts, and customize the Configuration and Settings scripts.

## Download and Installation

There should be a "Download ZIP" button on the [GitHub page](https://github.com/DonovanChan/EmailPro). Press that and open the EmailPro.fmp12 file. Its README script contains installation instructions.

## Contact

Donovan Chandler  
donovan_c@beezwax.net
