jena-jsonld
===========

This is a RIOT adapter for JSON-LD, based on https://github.com/tristan/jsonld-java.

The adapter provides complete integration into jena including:

    model.read("data.jsonld") ;

    model.write(System.out, "JSON-LD") ;

This code currently depend on https://svn.apache.org/repos/asf/jena/Experimental/riot-output/.