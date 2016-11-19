##  Risks

- hasn’t been around long
    - will it be here in the long-term?

- unfamiliarity for the team, possible typos using `npm`

- lockfile conflicts?
    - **DO NOT edit `yarn.lock` manually**

- "It's not ready for production"

note:
    WRT to maturity I would like to remind people that the official npm client node.js is bundling has over 2300 open issues (and over 10,000 closed). One of the open issues results in corrupted bundles being pushed to the registry (meaning the bundle has to be re-published with an incremented version) and was originally filed in 2014 and only addressed earlier this year.
    The npm client is definitely older than yarn by far but that doesn't make it stable. Also, yarn's development started in January and has seen some internal use before it went public.
