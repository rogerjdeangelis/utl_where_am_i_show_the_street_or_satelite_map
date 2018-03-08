# utl_where_am_i_show_the_street_or_satelite_map
Where am I. Show the street or satelite map. Keywords: sas sql join merge big data analytics macros oracle teradata mysql sas communities stackoverflow statistics artificial inteligence AI Python R Java Javascript WPS Matlab SPSS Scala Perl C C# Excel MS Access JSON graphics maps NLP natural language processing machine learning igraph DOSUBL DOW loop stackoverfl SAS community.
    Where am I. Show me the local street or satelite map.

    github
    https://tinyurl.com/ydbpgls5
    https://github.com/rogerjdeangelis/utl_where_am_i_show_the_street_or_satelite_map

    StackOverflow
    https://tinyurl.com/yd6sy5nb
    https://stackoverflow.com/questions/49087040/how-to-get-the-exact-locationlatitude-and-longitude-of-us-using-python

    Wackadoodle3000 profile
    https://tinyurl.com/yb9ju35a


    INPUT
    =====

      Sitting in my home office on planet earth.


    PROCESS (Python working code)
    =============================

      from selenium import webdriver;
      a=webdriver.Chrome();
      a.get("https://www.google.com/maps");
      print(a.execute_script("window.location"));

    OUTPUT
    ======

     Google maps will atomatically open with a local street map

    NOTES
    =====

     1. After installing selenium you may need to install the latest
        chrome webdriver at

          https://chromedriver.storage.googleapis.com/index.html?path=2.36/

        Only the 32bit version is available but it works with the 64bit Win 7

     2. You may ened to ctl-alt-delete > services > end process for chromedriver.exe

    *          _       _   _
     ___  ___ | |_   _| |_(_) ___  _ __
    / __|/ _ \| | | | | __| |/ _ \| '_ \
    \__ \ (_) | | |_| | |_| | (_) | | | |
    |___/\___/|_|\__,_|\__|_|\___/|_| |_|

    ;

    %utl_submit_py64('
    from selenium import webdriver;
    a=webdriver.Chrome();
    a.get("https://www.google.com/maps");
    print(a.execute_script("window.location"));
    ');

