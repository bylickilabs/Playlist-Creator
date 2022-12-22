```yaml
Creating-
@echo off
Color C
Title Bylickilabs Playlist Creator
 
:welcome

echo.
echo.
echo                    Loading
echo                   ---------------------------------------
echo                   10%%% 
echo                   ---------------------------------------
ping localhost -n 3 >nul

cls
echo.
echo.
echo                    Loading
echo                   ---------------------------------------
echo                   20%%% 
echo                   ---------------------------------------
ping localhost -n 1 >nul

cls
echo.
echo.
echo                    Loading
echo                   ---------------------------------------
echo                   30%%% 
echo                   ---------------------------------------
ping localhost -n 1 >nul

cls
echo.
echo.
echo                    Loading
echo                   ---------------------------------------
echo                   40%%%
echo                   ---------------------------------------
ping localhost -n 1 >nul

cls
echo.
echo.
echo                    Loading
echo                   ---------------------------------------
echo                   50%%%
echo                   ---------------------------------------
ping localhost -n 1 >nul

cls
echo.
echo.
echo                    Loading
echo                   ---------------------------------------
echo                   60%%%
echo                   ---------------------------------------
ping localhost -n 1 >nul

cls
echo.
echo.
echo                    Loading
echo                   ---------------------------------------
echo                   70%%%
echo                   ---------------------------------------
ping localhost -n 1 >nul

cls
echo.
echo.
echo                    Loading
echo                   ---------------------------------------
echo                   80%%%
echo                   ---------------------------------------
ping localhost -n 1 >nul

cls
echo.
echo.
echo                    Loading
echo                   ---------------------------------------
echo                   90%%%
echo                   ---------------------------------------
ping localhost -n 1 >nul

cls
echo.
echo.
echo                      Bereit 
echo                   ---------------------------------------
echo                   100%%%
echo                   ---------------------------------------
ping localhost -n 1 >nul
echo.
echo                        Weiter mit beliebiger Taste
echo.
pause >nul 

:main
set mainput=0
cls
echo.
echo.
echo. --------------------------------------------------------------------------------
echo                                   Playlist-Creator
echo. --------------------------------------------------------------------------------
echo.
echo                               Treffen sie ihre Auswahl
echo                               ========================
echo.
echo.
echo.
echo         =====================================
echo         [1] Create Playlist
echo         -------------------------------------
echo         [2] Information
echo         [3] Contact
echo         -------------------------------------
echo         [4] Exit
echo         =====================================
echo.
set /p op=Auswahl:
echo.
echo.
if %op%==1 goto 1
if %op%==2 goto 2
if %op%==3 goto 3
if %op%==4 goto Exit
goto error

:1
Pushd %1
Pushd "%1"
dir /b >Playlist-Creator.txt
Pushd "%1"
dir /b /s *.mp* *.mp4* *.ogg* *.fla* *.mp3* *.ape* *.aac* *.wv* *.wav* >PlayerListe.m3u
echo.
goto main

:2
cls
echo.
echo                                 ###################
echo                                 ## Informationen ##
echo                                 ###################
echo.
echo.
echo      #######################################################################
echo      #                                                                     #
echo      #                  Willkommen zu meinem PlaylistCreator               # 
echo      #                                                                     #
echo      #     Wenn ihnen die Anwendung zusagt, Kontaktieren sie mich bitte    #
echo      #######################################################################
echo.
echo.
echo    ##########################################################################
echo    #                                                                        #
echo    #           Das erstellen der Playlist soll vereinfacht werden.          #
echo    #                                                                        #
echo    #       Kopieren sie die Anwendung einfach in das Hauptverzeichnis       #
echo    #           und starten sie diese. Das erstellen der Playlist,           #
echo    #               beginnt sofort und dauert ca.1 Sekunde...                #
echo    #            Es wird eine .m3u Datei zum abspielen generiert,            #
echo    #                                                                        #
echo    ##########################################################################
echo.
echo                            mit beliebiger Taste weiter...
pause >nul
goto main

:3
cls
echo.
echo                 Fragen, Anregungen, Fehler, Verbesserungen an:
echo.
echo                      Kontakt:   - Thorsten Bylicki
echo.
echo                                 - https://www.bylickilabs.de
echo.
echo                                 - https://Github.com/bylickilabs
echo.
echo.
pause 
goto main

:Exit
``` 
