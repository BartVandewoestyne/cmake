cmake_minimum_required(VERSION 2.8)

function(foobar x y)
  message("x=${x}, y=${y}")
  message("ARGC = ${ARGC}")    # number of arguments passed into the function
  message("ARGV0 = ${ARGV0}")
  message("ARGV1 = ${ARGV1}")
  message("ARGV2 = ${ARGV2}")
endfunction(foobar)

foobar(a b c)
