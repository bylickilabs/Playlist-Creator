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