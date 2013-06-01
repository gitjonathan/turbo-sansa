turbo-sansa
===========

Example JAR file creation with text file within it, and reading of that file 
as a resource from within the JAR file

    git clone git://github.com/gitjonathan/turbo-sansa.git
    cd turbo-sansa
    ant
    cd build/jar
    
    # if you want to see data.txt in the jar
    jar tf com.mccluskey.turbosansa.jar

    # to see it execute reading it
    java -jar com.mccluskey.turbosansa.jar

