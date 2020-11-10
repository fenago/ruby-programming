<img align="right" src="../logo.png">


Lab 13. Document processing and reporting
=============================================

### This lab covers

-   Reading and writing CSV data
-   Generating daily reports
-   Producing a comparison report
-   Generating customized printable reports

Though we’d all love to be video game programmers or lead developers for
the Next Big Web 2.0 multimedia experience, most programmers have less
glamorous problems to solve. This inevitably includes processing
documents exported from sources, ranging from legacy systems to
industry-standard SQL databases. Of course, collecting the data and
translating it into a useable form is only half the challenge.
Aggregated data then needs to be manipulated, analyzed, and formatted in
ways that clearly communicate what that data represents. The field of
reporting ranges from quick sales reports for a small business to
massive statistical analyses for the enterprise.

There are numerous canned solutions for processing one form of document
and translating it to another, or for running standard reports against
data. For many uses, these applications are the way to go. However,
these solutions aren’t golden hammers. When developing custom software,
it’s often desirable to get exactly the kinds of results you’re looking
for, instead of using prebuilt solutions that may or may not be what you
need. For this kind of problem, Ruby shines.

In This lab, we’ll be looking at several solutions to common
reporting problems. We’ll cover processing and formatting libraries such
as FasterCSV, and we’ll look at the lightweight reporting system,
Ruport. Through these solutions, you’ll be able to see how rolling your
own solutions isn’t as scary as it sounds. By providing a solid but
malleable foundation to work from, Ruport provides a way to quickly
build your own customized reporting applications.

We’ll start with simple CSV processing to show off FasterCSV’s feature
set, then show how to use Ruport’s code generator to trivially script a
database-backed report that automatically emails its results when run.
We’ll then show how you can use Ruby’s text-processing capabilities to
compare a CSV file to a nonstandard data format. After covering the ins
and outs of data manipulation, we’ll dive into printable documents,
showing how you can leverage Ruport and PDF::Writer to generate
attractive customized PDF reports. Finally, we’ll talk about how to
optimize for performance when dealing with large datasets in Ruport.
