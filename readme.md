# Les Houches Predoc School on Cold Atoms: Quantum Gases and Quantum Fluids of Light

## Edit the template

Most of the configuration can be found in the config.yml file.
Edit this to access most of the parameters.

Images are stored in static/img/

Speakers infos are in data/speakers.yaml

Other files should not be edited

## Run it locally
hugo serve

## For Developpers
- First you need to duplicate the repo
- Then modify it and push to GitHub
- Link it to Netlify : command hugo, directory public
- Check the form ID to collect in Netlify forms (after enabling it)
- Connect to Zapier and link your form to a google sheeet
- Link to your domain:
    - Go to domain management in  Netlify > Site
    - Add a domain alias
    - Do it in OVH (or somewhere else) with a CNAME towards Netlify site adress
    - Go to Netlify Domain > Register the subdomain
    - Ask for a certificate 
