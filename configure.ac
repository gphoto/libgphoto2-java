dnl This is just a fragment to be extended to real configure.ac

dnl Check for SWIG

AC_PATH_PROG([SWIG], [swig])
AC_SUBST([SWIG])
AM_CONDITIONAL([HAVE_SWIG], [test -x "$SWIG"])

AC_PATH_PROG([JAVAC], [javac])
AC_SUBST([JAVAC])
AC_PATH_PROG([JAVA], [java])
AC_SUBST([JAVA])
AM_CONDITIONAL([HAVA_JDK], [test -x "$JAVAC" && test -x "$JAVA"])

if false && test -x "$SWIG" && test -x "$JAVAC" && test -x "$JAVA"; then
   bindings="${bindings}${bindings+ }java"
fi
