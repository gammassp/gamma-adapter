# Overview

```
Module Name:  Gamma Bid Adapter
Module Type:  Bidder Adapter
Maintainer: support@gammassp.com
```

# Description

Connects to Gamma exchange for bids.

Gamma bid adapter supports Banner, Video.

# Test Parameters
```
var adUnits = [{
          code: 'aaa',
          sizes: [[300, 250]],
  
          // Replace this object to test a new Adapter!
          bids: [{
			bidder: 'gamma',
            params: {
				siteId: '1465446377',
				zoneId: '1515999290',
				gaxDomain: 'hb.gammaplatform.com'
            }
          }]
  
        }];
```
