# capsule
Gemini capsule for nnix.com (proxied to https from gemini, so it's on both protocols)

## use
Files uploaded here are referenced by the nnix.com gemini server (nnix/gemini:latest droplet). They will be served via gemini:// on that server using :1965, and proxied to https:// through nginx on :443.

## gemlog
The gemlog folder contains all log entries. Dates should be in ISO 8601 format (YYYY-MM-DD) when linking, as-in this example:

```
## Posts
=> bokashi.gmi  2020-11-20 - Early Bokashi composting experiments
=> finite-simple-groups.gmi 2020-11-13 - Trying to get to grips with finite simple groups
=> garden.gmi  2020-11-06 - I started a garden.
```

## food
The food folder contains recipes. Same as the gemlog, Dates should be in ISO 8601 format (YYYY-MM-DD) when linking from the main list.

```
## Food
=> beef-bourguignonne.gmi  2020-11-20 - Stew.
=> toronto.gmi 2020-11-13 - Fernet-rye cocktail.
=> rogan-josh.gmi  2020-11-06 - Lamb curry.
```