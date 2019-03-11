# GooEat Service

# Exec this project

1. Add your dir to google cloud keys in application.properties file.
`spring.cloud.gcp.credentials.location=file:/dir/to/google-keys.json`
2. Exec mvn spring-boot:run
3. Then you can exec queries as follows:
`curl -d "imageUrl=http://www.elhuertodelabuelo.es/37-large_default/tomate-cana-andaluz.jpg" 127.0.0.1:8080/extractLabels`
