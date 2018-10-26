# PURL configuration for http://purl.obolibrary.org/obo/dpo
# Note that for historical reasons DPO uses the FBdv IDSPACE,
# but we want a top-level dpo.owl PURL.
# See also the fbcv.yml file.

idspace: DPO
base_url: /obo/dpo

products:
- dpo.owl: https://raw.githubusercontent.com/FlyBase/flybase-controlled-vocabulary/master/releases/dpo.owl

term_browser: ontobee
example_terms:
- FBdv_0000670

entries:
