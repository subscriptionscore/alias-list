# Subscription Score Domain Alias List

In some cases we wish to associate a public website with a mailing list domain.

For example Facebook send emails from the domain `facebookmail.com`, but we wish the score for this domain to be returned when we perform a search for `facebook.com`.

For our purposes `facebookmail.com` and `facebook.com` are aliased.

## Contributing

If you think we should add an alias then either open an [issue][1] and request it, or...

Modify the file `/alias-list.dat`, adding your alias in the form;

```
<public domain>: <mailing list domain>
```

For the facebook example above:

```
facebook.com: facebookmail.com
```

If a domain sends from from multiple mailing list domains, then simply include it in the list twice.

An hypothetical example being;

```
facebook.com: facebookmail.com
facebook.com: facebooknotifications.com
```

[1]: https://github.com/subscriptionscore/alias-list/issues
