comments: true
date: 2012-07-31 12:31:08
layout: post
slug: map-domain-wordpress-blog
title: How-To map a non-US domain name to a WordPress.com blog
wordpress_id: 5041
category: English
tags: Blog, dns, internet, SOA, WordPress, WordPress.com

I'm currently migrating most of my self-hosted WordPress blogs from my server to [WordPress.com hosting](https://en.wordpress.com/features/), which allows you to [use your own domain](http://en.support.wordpress.com/domain-mapping).

But setting the DNS records from your registrar may trigger some errors. I myself wasn't able to properly update my domain configuration and [OVH](http://ovh.com) always sent me back this notification email each time I tried to update the DNS record of `mydomain.fr`:


    
    :::text
    DNS update failed. Fix the zone-check error, and relaunch the operation.
    The zone-check error is: [TEST SOA record exists]: answer refused by the server: (SOA mydomain.fr)
    



This errors is mostly due to the use of a non-US domain.

To fix this `SOA`-related issues, the only extra step required consist in [asking WordPress.com to set a zone record](http://en.support.wordpress.com/domain-mapping/dns-zone-records/) on their servers. After that, you can proceed to the [standard mapping procedure](http://en.support.wordpress.com/domain-mapping/map-existing-domain/#instructions-for-mapping-an-existing-domain).