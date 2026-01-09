
.. _program_listing_file_googletest_googlemock_README.md:

Program Listing for File README.md
==================================

|exhale_lsh| :ref:`Return to documentation for file <file_googletest_googlemock_README.md>` (``googletest/googlemock/README.md``)

.. |exhale_lsh| unicode:: U+021B0 .. UPWARDS ARROW WITH TIP LEFTWARDS

.. code-block:: markdown

   # Googletest Mocking (gMock) Framework
   
   ### Overview
   
   Google's framework for writing and using C++ mock classes. It can help you
   derive better designs of your system and write better tests.
   
   It is inspired by:
   
   *   [jMock](http://www.jmock.org/)
   *   [EasyMock](https://easymock.org/)
   *   [Hamcrest](https://code.google.com/p/hamcrest/)
   
   It is designed with C++'s specifics in mind.
   
   gMock:
   
   -   Provides a declarative syntax for defining mocks.
   -   Can define partial (hybrid) mocks, which are a cross of real and mock
       objects.
   -   Handles functions of arbitrary types and overloaded functions.
   -   Comes with a rich set of matchers for validating function arguments.
   -   Uses an intuitive syntax for controlling the behavior of a mock.
   -   Does automatic verification of expectations (no record-and-replay needed).
   -   Allows arbitrary (partial) ordering constraints on function calls to be
       expressed.
   -   Lets a user extend it by defining new matchers and actions.
   -   Does not use exceptions.
   -   Is easy to learn and use.
   
   Details and examples can be found here:
   
   *   [gMock for Dummies](https://google.github.io/googletest/gmock_for_dummies.html)
   *   [Legacy gMock FAQ](https://google.github.io/googletest/gmock_faq.html)
   *   [gMock Cookbook](https://google.github.io/googletest/gmock_cook_book.html)
   *   [gMock Cheat Sheet](https://google.github.io/googletest/gmock_cheat_sheet.html)
   
   GoogleMock is a part of
   [GoogleTest C++ testing framework](https://github.com/google/googletest/) and a
   subject to the same requirements.
