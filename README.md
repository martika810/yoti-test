# yoti-test - Marta Rey

<h1>How to run the code</h1>

Requirement: Java 8

Once code is downloaded  :
  
  1.  mvn clean install
  2.  mvn jetty:run (to deploy the code in jetty server)
  
  The hoover functionality is available under: http://localhost:8080/robotic-hoover/rest/hoover (PUT method)

  Note: One possible problem you may encounter is that maven is not able to resolve the jetty plugin, in that case add the following in settings.xml
  <br>
  <br>
  <textarea>
    <pluginGroups>
       <pluginGroup>org.eclipse.jetty</pluginGroup>
     </pluginGroups>
  </textarea>

