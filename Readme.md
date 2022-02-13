How to migrate:

go install -tags 'postgres' github.com/golang-migrate/migrate/v4/cmd/migrate@latest</br>
cd ~/sdk/go1.18beta2/pkg/mod/github.com/golang-migrate/migrate/v4@v4.15.1/cmd/migrate/<br/>
go install .<br/>
=========<br/>
migrate create -ext sql -dir ./schema -seq init
