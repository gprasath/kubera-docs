---
title: Benchmarking your storage
shortTitle: FIO tests
#intro: '{% data variables.product.prodname_ghe_server %} supports the same powerful API available on {% data variables.product.prodname_dotcom_the_website %} as well as its own set of API endpoints.'
redirect_from:
  - /kubera-propel/benchmarking-your-storage
versions:
  free-pro-team: '*'
---

Benchmarking helps us to gain an understanding of your underlying infrastructure and also co-relate and ensure if the environments have been correctly set up. Storage benchmarking has always taken precedence and importance when your environment stack has stateful applications. This is useful for burn-in testing and it's always beneficial to perform stress tests on the system with additional loads.
Similarly using Kubera Propel, you can perform the Storage test.

To perform the storage test:

* Click on the <b> Run Test</b> for running the benchmarking. 


<a href="/assets/images/propel14.png" target="_blank"><img class="image-with-border" src="/assets/images/propel14.png"></a>

Kubera Propel uses the Fio tester against the underlying PV for performing the storage benchmarking. This Fio test analysis will help you with detecting the “Average IOPS”, “Average Throughput and Latency”.

Once you click on <b>Run Storage Test</b>, the next screen will let you create the test where you can add the “Test Name” as per your choice.

<br><br>
<a href="/assets/images/CreateFIOTest.png" target="_blank"><img class="image-with-border" src="/assets/images/CreateFIOTest.png"></a>
<br><br>
You can also select the “Storage Class” which you created earlier.
<br><br>
Finally click on <b>Run a performance test</b>
<br><br>
Lastly, after the Fio test gets completed, it will share the results of “Average IOPS, Throughput and Average latency if any”. You can also click on “View Report” to get a detailed view of the FIO tests performed. Historical tests can also be viewed from the same screen and the specific test can be rerun or reviewed to identify the performance calculated by FIO for that test case with “Read  and Write IOPS”, “Read and Write latency”. Export of the results can be done by clicking on <b>Export to PDF</b>.


<a href="/assets/images/propel18.png" target="_blank"><img class="image-with-border" src="/assets/images/propel18.png"></a>
<br><br>
