---
id: -44 
title: Test Suite Reduction Methods that Decrease Regression Testing Costs by Identifying Irreplaceable Tests
layout: researchpaper_n
categories: [research, paper, journal, regression testing]
authors: Chu-Ti Lin, Kai-Wai Tang, and Gregory M. Kapfhammer
mapped: true 
header: false 
research: false 
paper: true
backup: ../../../../../
---

## {{ page.title }} [<i class="fa fa-download"></i>]({{site.baseurl}}download/research/papers/ist2014-lin-tang-kapfhammer.pdf "Download this Paper!")

### {{page.authors }}

### <i>Information and Software Technology</i>, (54)10, October 2014.

### Abstract

<em>Context</em>: In software development and maintenance, a software system may frequently be updated to meet rapidly
changing user requirements. New test cases will be designed to ensure the correctness of new or modified functions, thus
gradually increasing the test suite’s size. Test suite reduction techniques aim to decrease the cost of regression
testing by removing the redundant test cases from the test suite and then obtaining a representative set of test cases
that still yield a high level of code coverage.

<em>Objective</em>: Most of the existing reduction algorithms focus on decreasing the test suite’s size. Yet, the
differences in execution costs among test cases are usually significant and it may take a lot of execution time to run a
test suite consisting of a few long-running test cases. This paper presents and empirically evaluates cost-aware
algorithms that can produce the representative sets with lower execution costs.

<em>Method</em>: We first use a cost-aware test case metric, called Irreplaceability, and its enhanced version, called
EIrreplaceability, to evaluate the possibility that each test case can be replaced by others during test suite
reduction. Furthermore, we construct a cost-aware framework that incorporates the concept of test irreplaceability into
some well-known test suite reduction algorithms.

<em>Results</em>: The effectiveness of the cost-aware framework is evaluated via the subject programs and test suites
collected from the Software-artifact Infrastructure Repository — frequently chosen benchmarks for experimentally
evaluating test suite reduction methods. The empirical results reveal that the presented algorithms produce
representative sets that normally incur a low cost to yield a high level of test coverage.

<em>Conclusion</em>: The presented techniques indeed enhance the capability of the traditional reduction algorithms to
reduce the execution cost of a test suite. Especially for the additional Greedy algorithm, the presented techniques
decrease the costs of the representative sets by 8.10–46.57%

