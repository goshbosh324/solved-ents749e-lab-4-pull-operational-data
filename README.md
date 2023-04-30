Download Link: https://assignmentchef.com/product/solved-ents749e-lab-4-pull-operational-data
<br>
<ol>

 <li>Write and execute a Python script that displays the router’s uptime information and load averages on the screen. First, create a code skeleton based on the one provided on the slides and make sure that you:

  <ul>

   <li>access the correct networking device</li>

   <li>import the necessary libraries,</li>

   <li>use the try/except/finally blocks as shown on the slides and handle exceptions occurred during the NETCONF session.</li>

  </ul></li>

 <li>Connect to the device and make sure that the connection is successful.</li>

 <li>Add code that calls the correct RPC (hint: the corresponding CLI command is: show system uptime), and dump the RPC response on the screen to see if the RPC call was successful.</li>

 <li>Add code that extracts the following information from the RPC response, and displays it on the screen:

  <ul>

   <li>the system boot time (the date and the time the device was last booted), the number of days, hours and minutes the device has been up and running, <sup>•</sup>         the 1-minute, 5-minute and 15-minute load average values.</li>

  </ul></li>

</ol>

Part II

<ol>

 <li>Write and execute a Python script that displays the following information about all 16 physical interfaces in your router:</li>

</ol>

<ul>

 <li>the interface name (e.g. ge-0/0/5)</li>

 <li>the administrative status (up or down)</li>

 <li>the operational status (up or down)</li>

 <li>if the operational status is “up” it should also display the IPv4 address configured on that interface (this is called the “local interface address”)</li>

 <li>its MAC address (it is called the “hardware physical address”)</li>

</ul>

Make sure that you catch and handle all exceptions that may occur during the NETCONF session. Hint: the corresponding CLI command is: show interfaces ge*, where the interface name pattern “ge*” will become an RPC parameter.













1


