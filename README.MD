chạy trên môi trường phát triển (localhost)

`
mvn jetty:run -Djetty.host=localhost -Djetty.port=8080
`

chạy trên môi trường sản xuất (server)
`
mvn jetty:run -Djetty.host=0.0.0.0 -Djetty.port=8080
`