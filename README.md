
# Base data retriever

This service is responsible for retrieving data from a normalized database, in
a UNIT-TIME long form format. The service acts as the translator between these
two data formats.

It does so by reflecting the relational structure of the database to figure out
how to join tables, in order to produce the desired output format.
