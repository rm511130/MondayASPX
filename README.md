# MondayASPX
Simple ASPX .NET Example

- Visual Studio 2015 .NET Sample Application
- Small memory footprint
- 'cf push' leverages manifest.yml
- Requires Windows Stack on PCF
- 'cf push' will generate a random-route for the Application

    <dependencyManagement>
        <dependencies>
          <dependency>
            <groupId>org.springframework.cloud</groupId>
            <artifactId>spring-cloud-starter-parent</artifactId>
            <version>Brixton.M1</version>
            <type>pom</type>
            <scope>import</scope>
          </dependency>
        </dependencies>
    </dependencyManagement>
