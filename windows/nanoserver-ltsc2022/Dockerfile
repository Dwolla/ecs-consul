# escape=`

FROM dwolla/consul:1.0.6-3-nanoserver-ltsc2022-amd64
COPY entrypoint.bat C:/entrypoint.bat

# Running as ContainerAdministrator is needed to add routes for accessing the AWS metadata and credentials APIs.
USER ContainerAdministrator
ENTRYPOINT ["C:\\entrypoint.bat"]