# Rules for the test code (use `make check` to execute)
TESTS = MoneyApp
bin_PROGRAMS = $(TESTS)
MoneyApp_SOURCES = Money.h MoneyTest.h MoneyTest.cpp MoneyApp.cpp
MoneyApp_CXXFLAGS = $(CPPUNIT_CFLAGS)
MoneyApp_LDADD = -lcppunit

