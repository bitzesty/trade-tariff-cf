# trade-tariff-cf

setup:

https://documentation.trial.cf.paas.alphagov.co.uk/getting-started/setup/

cf target -o "tradetariff.gov.uk" -s "dev"
cf target -o "tradetariff.gov.uk" -s "prod"

Plan:

Have all apps running within one space:

[] errbit (try this fork https://github.com/cph/errbit)
[] signonatron2
[] trade-tariff-backend
[] trade-tariff-frontend
[] trade-tariff-admin

We'll need a massive manifest we'll see if this works...

https://docs.cloudfoundry.org/devguide/deploy-apps/manifest.html#multi-apps
