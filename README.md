# ep-doppelganger

A first-steps project using Sencha and PhoneGap

## Running Adobe PhoneGap Build

1. Verify that Sencha Touch (>4.0) and PhoneGap (>3.4) are installed.
2. Clone repo.
3. Sign up or log into your Adobe PhoneGap account
4. Build using private build service
    1. In your local version of the project, verify that phonegap.local.properties has:
        1. phonegap.platform set to the list of platforms you want to build
        2. phonegap.build.remote set to "true"
        3. phonegap username and password.
    2. Now run: `sencha app build -run native`
5. Note that the public PhoneGap build service is not feasible as the minimum size for the combined Sencha-Phonegap project is too large for Adobe's public build service.