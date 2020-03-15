FROM centos

RUN yum -y install dotnet
RUN yum -y install git
RUN mkdir /app
COPY . /app
RUN dotnet build /app
EXPOSE 5000-5001
RUN dotnet run --project=/app
