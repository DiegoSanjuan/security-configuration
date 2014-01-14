DHE parameter
==============

… can be generated using OpenSSL:

    openssl dhparam -rand random_bytes.seed 3072 -out my.dhparam-3072

The ENISA recommends 3072 bits or more [1].

[1] http://www.enisa.europa.eu/activities/identity-and-trust/library/deliverables/algorithms-key-sizes-and-parameters-report – page 35

