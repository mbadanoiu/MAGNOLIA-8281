# MAGNOLIA-8281: FreeMarker Restriction Bypass 2 in Magnolia CMS

An issue in the FreeMarker Filter of Magnolia CMS v6.2.16 and below allows attackers to bypass security restrictions and read/write/move/copy/delete arbitrary files via a crafted FreeMarker payload. Arbitrary code execution was successfully achieved via writing arbitrary JSP files.

### Vendor Disclosure:

The vendor's disclosure and fix for this vulnerability can be found [here](https://docs.magnolia-cms.com/product-docs/6.2/releases/release-notes-for-magnolia-cms-6.2.17/).

### Why no CVE?

Neither me nor the vendor requested a CVE for these vulnerabilities.

### Proof Of Concept:

More details and the exploitation process can be found in this [PDF](https://github.com/mbadanoiu/MAGNOLIA-8281/blob/main/Magnolia%20CMS%20-%20MAGNOLIA-8281.pdf).

### Additional Resources:

The JSP code used to execute arbitrary system commands can be found [here](https://gist.github.com/nikallass/5ceef8c8c02d58ca2c69a29a92d2f461)
