# RaBe Ontologies

This repo contains some early work on ontologies for expressing a radio station in an RDF store.

* cs/ contains a copy (fork if you will) of `urn:ebu:metadata-cs:ContentGenreCS_20100803` with a simple patch for i18n
* locale/ contains a "mostly there", but unfinished translation of ContentGenreCS to the `de` locale
* owl/fm defines `FmChannel` as an additional `&ebucore;PublicationChannel` for representing UKW transmissions
* owl/rds-pi extends `FmChannel` with RDS-PI metadata

This never found any real production use. I'm leaning towards archiving this repo, but can't let go yet.

Please reach out if you see value in keeping, and potentially updating & modernising, things like
the `https://raw.github.com/radiorabe/ontologies/master/owl/fm#` xml-ns or the i18n efforts.

RaBe generates a lot of raw data, volunteer data scientists that help us model this into true open data would be very welcome.
