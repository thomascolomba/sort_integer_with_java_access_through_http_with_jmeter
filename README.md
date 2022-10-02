# sort\_integer\_with\_java\_access\_through\_http\_with\_jmeter

A Jmeter scenario test doing a http GET request to servlet sorting ints. <br/>
(JMeter 5.5)<br/>



<br/>
-- test_local_tomcat_sorting_integers.jmx<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;stringProp name="Argument.value"&gt;6,8,3&lt;/stringProp&gt; <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;stringProp name="Argument.name"&gt;intsToSort&lt;/stringProp&gt; <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;stringProp name="HTTPSampler.path"&gt;/sort_integer_with_java_and_servlet_and_webxml/sortIntegers&lt;/stringProp&gt;<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;stringProp name="HTTPSampler.method"&gt;GET&lt;/stringProp&gt; <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;stringProp name="HTTPSampler.domain"&gt;127.0.0.1&lt;/stringProp&gt; <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;stringProp name="HTTPSampler.port"&gt;8080&lt;/stringPro&gt; <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&lt;stringProp name="HTTPSampler.protocol"&gt;http&lt;/stringProp&gt; <br/>
<br/>
![screenshot of http_request_default_parameters](https://github.com/thomascolomba/sort_integer_with_java_access_through_http_with_jmeter/blob/main/jmeter_http_request_parameters.png?raw=true) <br/>
![screenshot of http_request_parameters](https://github.com/thomascolomba/sort_integer_with_java_access_through_http_with_jmeter/blob/main/jmeter_http_request_parameters.png?raw=true) <br/>
![screenshot of http_response](https://github.com/thomascolomba/sort_integer_with_java_access_through_http_with_jmeter/blob/main/jmeter_http_response.png?raw=true) <br/>
<img src="./jmeter_http_response.jpg" alt="screenshot of response">
