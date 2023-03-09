Burp Spider is a Burp Suite plugin that enables users to crawl a website using Burp Suite's built-in spider. The plugin implements the IScannerCheck interface and uses the sendToSpider method to send the URL to Burp Suite's spider for crawling.</br>

<br>This tool is useful for performing web application security testing and identifying hidden or undiscovered pages and endpoints on a website.</br>

<br>To use the Burp Spider tool, simply load the plugin into Burp Suite and start an active scan. The plugin will automatically send discovered URLs to the spider for crawling.</br>

Requirements
Java Development Kit (JDK) 8 or later
Burp Suite Pro or Community Edition 2.1.0 or later
Burp Extender API

Installation
Download the latest release of the Burp Spider plugin from the Github repository.
In Burp Suite, go to the "Extender" tab and select "Extensions".
Click the "Add" button and select the downloaded JAR file.
The plugin should now be loaded and ready to use.

Usage
Start an active scan on a website using Burp Suite.
The Burp Spider plugin will automatically send discovered URLs to the spider for crawling.
Once the spider has completed crawling, the discovered URLs will be listed in the "Site map" tab.


Contributing
If you have suggestions for new features or improvements to the Burp Spider tool, please feel free to submit an issue or pull request on Github.

Contact
If you have any questions or concerns about the Burp Spider tool, please feel free to contact me at support@viehgroup.com
