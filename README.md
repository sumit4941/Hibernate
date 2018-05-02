# Hibernate


java.lang.ClassNotFoundException: javax.xml.bind.JAXBException and java.lang.ClassNotFoundException: com.sun.xml.bind.v2.ContextFactory



Those who are running there Project under (Java-9)

step 1:

Download latest stable 5.2 jar from this link ( https://sourceforge.net/projects/hibernate/files/hibernate-orm/5.2.15.Final/hibernate-release-5.2.15.Final.zip/download ).

To find the required jar in downloaded 5.2

extract the Zip
2.open the extracted folder - goto lib folder - goto required folder -copy all jars +mySQL Driver jar and paste it in lib folder under src and do the build path
step 2:

--add-modules java.xml.bind (paste this line of code in VM arguments:)

just copy above line and paste in the VM arguments:
Where to find VM Arguments:

->go to run option
-> run configuration
->Arguments
->VM arguments (you will get input box below paste this line --add-modules java.xml.bind )
-> Apply
-> Run
