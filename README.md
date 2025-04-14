# tcs-schema
This repo relates to GWF's application of the Technology Carbon Standard (TCS) Schema via a carbon.txt file. 

- [About the TCS schema](https://www.techcarbonstandard.org/schema/techcarbonstandard).
- [About carbon.txt.](https://www.thegreenwebfoundation.org/tools/carbon-txt/)


## Why?

In order to support the principle of "openness as a key indicator for sustainability", we've been working with the [TCS team](https://www.techcarbonstandard.org/about) to make it easier to publicly disclose the results of a TCS digital estate emissions report as structured data.

Structured data is easier to make use of in a variety of ways, and lends itself nicely to automation. Only if you know the data is available and where to find it of course!

That's where one of our own projects, [carbon.txt](https://www.thegreenwebfoundation.org/tools/carbon-txt/), is a complementary solution. 

Carbon.txt is an approach to making machine-readable data easier to find and use.

By bringing these two parts together - the TCS Schema and carbon.txt - we are exploring a way to create much needed transparency in the field of digital estate emissions reporting.


## How?

We've been collaborating with the TCS team to define a [JSON schema](https://www.techcarbonstandard.org/schema/techcarbonstandard) that allows for the output of a TCS digital estate estimate to become standardised as structured and machine-readable data. 

Together we've defined a first version - v0.0.1 - of the JSON schema to meet this need.

Using our previously reported digital estate emissions estimates - produced using the TCS framework, [documented as a case study](https://www.thegreenwebfoundation.org/news/an-experience-report-using-the-tech-carbon-standard/) - our next step is apply the numbers we reported into the schema.

In this repo you will find our effort to take our estimates and and port them into the defined schema.

The resulting json file is then linked to from [our own public carbon.txt file](https://www.thegreenwebfoundation.org/carbon.txt).






