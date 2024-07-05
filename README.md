# AccuKnox
AccuKnox - problem statement


Ensure you have Java installed.
Add Selenium to your project. You can download the Selenium JAR files or add Selenium dependencies via Maven if you are using a build tool.

If you are using Maven, add the following dependencies to your pom.xml:

<dependencies>
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-java</artifactId>
        <version>4.1.0</version>
    </dependency>
    <dependency>
        <groupId>org.seleniumhq.selenium</groupId>
        <artifactId>selenium-chrome-driver</artifactId>
        <version>4.1.0</version>
    </dependency>
</dependencies>


Adjust the URL and Selectors: Ensure you update the frontendUrl and the selector used to locate the message element (By.id("message")) based on your specific frontend application.
Handle Page Load Time: Adjust the Thread.sleep(3000) duration if your application requires more or less time to load.
