job('Maven_Project_DSL') {
	description('First Maven Project with DSL created on ${new Date()}')
	scm {
		git("https://github.com/anshulc55/Jenkins_Upgradev3.git",master)
	}
	steps{
		maven('clean package', 'maven-samples/single-module/pom.xml')
	}
	publisher{
		archiveArtifcts '**/*.jar'
	}
}
