node 
{
	checkout scm
	docker.withRegistry('https://registry.hub.docker.com','Docker')
	{
		def customImage = docker.build("preranang/yes")
		customImage.push()
	}
}
