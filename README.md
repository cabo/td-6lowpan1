# ETSI 6LoWPAN plugtest Test Descriptions

This repository is used for collaborating on the Test Descriptions for
the first [ETSI 6LoWPAN plugtest][6lowplug].

This repo hosts a main "source" file and a generated file:

- test-descriptions.yml.  This is a [YAML][] file with a
  machine-readable form of the test descriptions.

- td1.html.  This is automatically generated from
  test-descriptions.yml.  Strictly speaking, it should not be under
  source control, but putting it here makes life easier.  It's not a
  train wreck to issue a pull request on this file, but you are
  probably better off editing the YAML.

Don't forget to [register][6lowplug] for the plugtest!  
(It's the well-hidden green button on that page...)

[6lowplug]: http://www.etsi.org/news-events/events/663-2013-6lowpan-plugtests
[YAML]: http://www.yaml.org/spec/1.2/spec.html
