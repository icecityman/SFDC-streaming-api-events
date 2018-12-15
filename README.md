# Salesforce Streaming API Events

## Streaming API
<ul>
<li>Streaming API is a specialized API for setting up notifications that trigger when changes are made to Salesforce data.</li>
<li>It uses a publish-subscribe, or pub/sub, model in which users can subscribe to channels that broadcast certain types of data changes.</li>
<li>The pub/sub model reduces the number of API requests by eliminating the need for polling.</li>
<li>Streaming API is great for writing apps that would otherwise need to frequently poll for changes.</li>
</ul>

## When to use Streaming API
<ul>
<li>Use Streaming API to receive near-real-time streams of data that are based on changes in Salesforce records or custom payloads.</li>
<li>For Salesforce record changes, Salesforce publishes notifications when the changes occur.</li>
<li>For custom notifications, you can publish event messages.</li>
<li>Subscribers can receive notifications using CometD—an implementation of the Bayeux protocol that simulates push technology.</li>
<li>Clients can subscribe to some types of events with Apex triggers or declaratively with Process Builder and flows.</li>
</ul>



## Streaming Events Features
<ol type="1">
<li>PushTopic</li>
<li>Generic Event</li>
<li>Platform Event</li>
<li>Change Data Capture (CDC)</li>
</ol>

## High Level Overview
<table>
	<tr>
		<th>API</th>
		<th>Protocol</th>
		<th>Data Format</th>
		<th>Communication</th>
	</tr>
	<tr>
		<td>Streaming API</td>
		<td>Bayeux</td>
		<td>JSON</td>
		<td>Asynchronous (stream of data)</td>
	</tr>
	<tr>
		<td>Platform Events</td>
		<td>CometD</td>
		<td>JSON</td>
		<td>Asynchronous (stream of data)</td>
	</tr>
</table>




## Useful Resources
<ul>
<li><a href="https://trailhead.salesforce.com/content/learn/modules/api_basics/api_basics_overview" target="_blank" alt="API Basics: When to Use Streaming API">API Basics: When to Use Streaming API</a></li>
<li><a href="https://trailhead.salesforce.com/content/learn/modules/api_basics/api_basics_streaming" target="_blank" alt="API Basics: Use Streaming API">API Basics: Use Streaming API</a></li>
<li></li>
</ul>

<img src="supportedimages/118.png"/>
