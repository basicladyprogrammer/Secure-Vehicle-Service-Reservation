# Secure-Vehicle-Service-Reservation-WebApp
A traditional web application for vehicle service reservation with a focus on security, authentication, and access control. This Web application is focused on mitigating the OWAPS top 10 vulnerabilities, mostly focusing on Broken Access Control, SQL Injection, and Cross-Site Scripting (XSS). Also, user authentication and access control have been implemented using OIDC protocols with a cloud-based Identity Provider (IDP), Asgardeo.

![VehicleCareReserve](https://github.com/basicladyprogrammer/Secure-Vehicle-Service-Reservation-WebApp/assets/84853907/4a985643-6aab-48da-bf1c-fdfdae2a99ec)

## Roadmap to Deploy

- Download the project as a Zip

- Extract it to your workplace

- Open the project using an IDE that supports dynamic web application development such as Eclipse.

- Go to the src->main->webapp->WEB-INF->authorization.properties and update with your credintials.
  (You must have an Asgardeo account with an application and at least one user)

- Check whether the required jars are available in the lib folder.
  (mysql-connector-j-8.1.0 and org.json jars)

- If not download them and configure them to the project.

- Run the index.jsp as the entry point on the Tomcat server

## Reference

 - [You can find the Blog Article about VehicleCareReservation](https://medium.com/@sutharsirajan/building-a-secure-webapp-with-oidc-and-defend-against-top-owasp-vulnerabilities-6578f818cff3)
