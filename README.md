# IoT Engineering
## Hands-on of lesson 7
For slides and example code, see [lesson 7](../../../fhnw-iot/blob/master/07/README.md)

> *Note: Do not work on this repository right away.*<br/>
> *[Check existing forks to find the specific repository for your class.](../../network/members)*

### a) MQTT command line, 5'
* Install the mqtt CLI tool on the Raspberry Pi.
* Connect to the broker test.mosquitto.org
* Subscribe to the topic fhnw-iot/names
* Send your name to the same topic.
* (Open a second terminal)

### b) MQTT pub/sub clients, 5'
* Install the mqtt Node.js library on the Raspberry Pi.
* Run the previous MQTT pub/sub client examples.
* Use the _.js_ link on each page or check the main repo.
* To run a Node.js program _my.js_, type: ```$ node my.js```

### c) Local MQTT broker, 15'
* Install and run the mosquitto broker on Raspberry Pi:<pre>
    $ sudo apt-get update
    $ sudo apt-get install mosquitto # port 1883</pre>
* Test with the ESP8266 publisher/subscriber clients.
* Use the _.ino_ link on the page or check the main repo.
* Check ```$SYS/broker/clients/connected``` on the Pi.

### d) Data formats, 15'
* Choose one of the [Grove sensors](https://github.com/tamberg/fhnw-iot/wiki/Grove-Sensors) listed in the Wiki.
* Define a suitable JSON format to transmit its data.
* Translate the format into a [Protobuf .proto file](https://developers.google.com/protocol-buffers/docs/proto).
* Done? Build the parser for Node.js or Arduino.

### Submitting results
* [Commit and push](#git) local changes to your repository.
* Want a review? [Create an issue](../../issues/new), mention me (@tamberg).

## Tools
### Git
On your computer
* In the hands-on repository [fork for your class](../../network/members), in README.md, click the _GitHub Classroom link_.
* Once you accept the assessment, you get a personal, private repository URL for your _USER_NAME_:<pre>
http://github.com/fhnw-iot-CLASS/fhnw-iot-work-07-USER_NAME</pre>

On your computer or Raspberry Pi
* Clone the repository<pre>
    $ cd ~
    $ git clone REPO_URL</pre>
* Add a file<pre>
    $ git add FILE</pre>
* Commit changes<pre>
    $ git commit FILE -m "Fixed all bugs"</pre>
* Push changes<pre>
    $ git push</pre>

## Wiki
- [IoT Engineering Wiki](https://github.com/tamberg/fhnw-iot/wiki)

## Support
- [IoT Engineering Slack](https://fhnw-iot.slack.com/)
