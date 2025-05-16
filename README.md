# CloudinaryTutor
in spring boot intializer add dependencies like:
Web Reactive(Flux)
r2dbc

dependency for mysql :
<dependency>
			<groupId>io.asyncer</groupId>
			<artifactId>r2dbc-mysql</artifactId>
			<version>1.1.3</version>
		</dependency>
  
  dependency for cloudinary:
  <dependency>
			<groupId>com.cloudinary</groupId>
			<artifactId>cloudinary-http44</artifactId>
			<version>1.29.0</version>
		</dependency>
if this dependency lighted up thats mean that this dependency has susceptible http client version and u need to add this dependency
<dependency>
			<groupId>org.apache.httpcomponents</groupId>
			<artifactId>httpclient</artifactId>
			<version>4.5.13</version>
		</dependency>

  and API keys for Cloudinary 
cloudinary.cloud-name=
cloudinary.api-key=
cloudinary.api-secret=

and add CloudinaryConfig
