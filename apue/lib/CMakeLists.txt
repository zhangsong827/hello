# 定义源文件列表
add_library(apue SHARED 
                                bufargs.c       errorlog.c   popen.c    recvfd.c      setfd.c       spipe.c
                                cliconn.c       lockreg.c    prexit.c   semaph.c      setfl.c       strerror.c
                                clrfl.c         locktest.c   prmask.c   senderr.c     signal.c      tellwait.c
                                CMakeLists.txt  nspipe.c     ptyfork.c  sendfd.c      signalintr.c  ttymodes.c
                                daemonize.c     openmax.c    ptyopen.c  servaccept.c  sleep.c       writen.c
                                error.c         pathalloc.c  readn.c    servlisten.c  sleepus.c
)
