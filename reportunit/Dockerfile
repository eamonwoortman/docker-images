FROM minty/alpine-mono-nuget
RUN nuget install ReportUnit -Version 1.5.0-beta1
ENTRYPOINT ["mono", "./ReportUnit.1.5.0-beta1/tools/ReportUnit.exe"]