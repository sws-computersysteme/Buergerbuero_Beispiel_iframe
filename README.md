
# SWS Settings

 
You can customize your iframe by adding certain query parameters to the source URL

  

## Iframe

  

With the Iframe-View of our page, only the cards and the footer are displayed.
Its recommended to always use this setting when implementing our page over a iframe.

  

Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?iframe=true"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?iframe=true)

  

## Footer

  
Setting the footer parameter to false will hide the logos and the imprint-link
If you want to implement a single card in your page, this setting is recommended

  

Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?footer=false"></iframe>

</div>

```

## Card Mode

  
With these filters, the size of the card is changed. The following options are available here:

- default
- medium
- big

  

Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?size=big"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?footer=false)

  

## Detach

  

Setting detach to true will change the functionaliy of the "book appointment" Button

If its true, the button will open the scheduler view in a new tab
If your iframe is very small the setting is recommended

  

Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?detach=true"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?detach=true)

  

## Filters

  

If you want to filter the displayed Meeting Cards you can use serveral filter-parameters:

  

### Filter with ID

  
Only the card with this special meeting-id appears:


Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?id=5f451ae6c669b00010ca436b"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?id=5f451ae6c669b00010ca436b)

  

-------------------------------

  
Its also possible to pass multiple id's by seperating them with a "-" :

  
Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?id=5f451ae6c669b00010ca436b-5f45059b6185c8001149c8e7"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?id=5f451ae6c669b00010ca436b-5f45059b6185c8001149c8e7)

  
  

### Filter with Type

  

If you filter with the type you can decide, whether all Personal Meeting Room cards (type=pmr) or events (type=event) are displayed:

  

Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?type=pmr"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?type=pmr)

  
  

### Filter with Categories

  

In the Agent Interface you can also define custom categories, which then can be used to filter.

In our Case we created the category "DokuDemo" and applied it to 2 of our cards:

  
  

Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?categories=DokuDemo"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?categories=DokuDemo)

  
  

-----

  

Its also possible to combine categories:

  

Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?categories=DokuDemo-AnotherOne"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?categories=DokuDemo-AnotherOne)

  
  
  

### Combining Filters

  

All possible filter methods can be combined:

  

Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?categories=AnotherOne&id=5f451a83c669b00010ca436a"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?categories=AnotherOne&id=5f451a83c669b00010ca436a)

  

## Combinig URL-Parameters

  

All Parameters can be used at the same time

In this Exmple we created a URL that hides footer and header, detaches the "book appointment" button and filters with a id:

  
  

Example:

```

<div>

<iframe id="sws_iframe" src="https://swsdemo.parteiverkehr.de/?iframe=true&footer=false&detach=true&id=5f451ae6c669b00010ca436b"></iframe>

</div>

```

  

Click here to view our demo: [Demo](https://swsdemo.parteiverkehr.de/?iframe=true&footer=false&detach=true&id=5f451ae6c669b00010ca436b)

  

# iFrame-Reziser
We are using Iframe Resizer for this Project

Copyright © 2013-20 David J. Bradshaw. Licensed under the MIT License.
To see the Documentation click the follwoing Link: [Iframe-Resizer](https://github.com/davidjbradshaw/iframe-resizer/blob/master/README.md)