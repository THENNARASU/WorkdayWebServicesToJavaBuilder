Author: Thenn Eswaran

To use this within github codespaces,

sudo apt update -y

sudo apt install ant -y

sudo apt install jaxb -y


1) Add the .xsd or .wsdl file inside XSD or WSDL directory.
   
2) Build.xml for the following
    schema.type -> XSD or WSDL
    package.qualifier -> XSD or WSDL file name without extension (avoid spaces and special chars, underscore and dashes are okay)
    package.loc -> Exploded location for the package
    package.name -> Your package name excluding the qualifier
   
3) ant clean dist-xsd (or) dist-wsdl
