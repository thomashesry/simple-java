node { 

// Mark the code checkout 'stage' 
stage 'Checkout' 

def mvnHome = '/usr/share/maven' 

// Mark the code build 'stage' 
stage 'Build' 

// Run the maven build 
sh "${mvnHome}/bin/mvn clean install" 

}