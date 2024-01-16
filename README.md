# Implant

```
I have an awesome moonshot idea for my MVP, let me buy a domain.
Cool! I bought moonshot-idea.com.
Now, I will quickly build a website, let me use website builders like Framer, Wix.

You remember it's MVP, pace matters, bla bla bla.

Ok! I ended up with a website like moonshot.framer.app or moonshot.wixsite.com. How do I
replace that with my purchased domain. Wait what, I will have to pay for hosting for
custom domain or I'm stuck with the suffix. That sucks!

I know fellow founders what pain you go through, that's why I built Implant
```

Implant is a hacky fix for the external suffixes for your moonshot ideas with a simple solution of embedding iframe of the published website builder websites (like framer, wix).

## Limitations

I have tested only with Firebase so far, feel free to test with other offerings like AWS Amplify.

## How to use

1. Use this official guide to create a [sample firebase hosting app](https://firebase.google.com/docs/hosting/quickstart)
2. Replace `public/index.html` with html generated from [Implant](https://implant.github.io).
3. Then you will have a working firebase app with the website builder website.
4. Final step is adding [custom domain to the firebase app](https://firebase.google.com/docs/hosting/custom-domain)
