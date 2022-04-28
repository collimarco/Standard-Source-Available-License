# Standard Source Available License (SSAL)

This is the official document that defines the "Standard Source Available License" (SSAL).

## License text

```
Copyright <YEAR> <COPYRIGHT HOLDER>

Use and modifications are permitted under the following conditions:

1. The above copyright notice and this permission must be retained in all copies.
2. The modifications to the software must not circumvent license key validations or other license-related code.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY DAMAGES OR OTHER LIABILITY.
```

## Motivations

This section describes the motivations for the creation and adoption of this license.

### Limits of open source licenses

Open source has great advantages, but, often, it is also a way for large corporations to exploit the work of independent developers.

This has produced a negative impact on the ecosystem, including:

- frustration of maintainers and sabotages (e.g. Faker)
- security vulnerabilities (e.g. Log4j, Heartbleed)
- widely-used software that is not well-maintained.

### A "standard" source available license

This license has the following qualities:

- Simple
- Inspired by permissive licenses
- Source available
- Makes monetization possible (e.g. for advanced features or for usage above certain thresholds)

There are already many projects (e.g. Redis modules, Gitlab EE) that use "Source Available" licenses,
but their licenses are complex and non-standard and that may limit the adoption of such projects (this is even more true for smaller projects).

Having a "Standard Source Available License" makes it easy for developers to use a "Source Available" license for their project.

It will also make it easier to use and modify a "Source Available" project, without worries about a strange clause somewhere.

A wide adoption of this license will make it legally required for larger organizations to buy a license and sponsor the project, with the result of happier contributors and well-maintained software.

## Questions

Disclaimer: this is not legal advice, but an interpretation of the license.

### Why another license?
If you use a traditional, permissive license, like MIT / BSD, it's difficult to monetize and sustain the software.
On the other hand, commercial licenses are difficult to understand and adopt because they impose too many restrictions and clauses.

### Why use this license instead of dual licensing (OSS + commercial)?
If you keep the commercial-licensed code private, collaboration becomes more difficult, like traditional proprietary software.
It is also difficult to understand the effects of the EULA, since they are always complex and non-standard.
From a marketing perspective, it can also be difficult to let the users try your commercial code.
Using this license, you have most freedoms of open source, easy distribution and collaboration, without the need of separate repositories, and a license that is easy to understand.

### Can I use SSAL-licensed software inside / with software under a different license?
This license does not limit your rights to use the software inside a software distributed with a different license.
However you need to keep the copyright and any license key validation or related code.
The final user may need to purchase a license key in order to use the aggregated software (unless he stays within a free tier).

### Is it open source?
Maybe. It depends on the meaning of "open source". 
From an official point of view, this license has never been submitted to OSI for approval, so it's not officially open source. 
However this license definitely grants most of the rights / freedoms of open source.

### Is it free software?
The software can be free, but there might be some advanced features or usage above certain levels that require the purchase of a license key.

### Is commercial use allowed?
Yes.

### What if someone ignores the license and circumvents the license validation?
That is always possible for any license and legal agreement.
However that would be illegal and most companies don't take the risk. 

### What is the intended use?
You can use this license for any software that is source available, but has also some paid features.
Basically your software will contain some code that validates a license key or similar.
The license key can be validated over the internet or simply with cryptography (e.g. JWT).
The license key is not always necessary: for example the basic version or the free tier may not require a license.

### How does the license propagate?
Anyone that receives the software will be free to use and modify the software, under the conditions of the license (copyright and, sometimes, the purchase of a license key).
This license does not prevent you from using the software together with other software.
When the copyright owner receives a contribution, under the original license, they still have the copyright (the copyright notice is not changed) and no other limitations (the only other requirement would be to not circumvent the license, but by definition, if you are the owner, you cannot infringe this clause).

## Usage

Feel free to use this license for your next project.

## Contributing

You can open a discussion or suggest improvements... 

If you like the idea, give it a star and spread the voice (e.g. blog post, Twitter).

## Credits

Originally created by [Marco Colli](https://collimarco.com).
