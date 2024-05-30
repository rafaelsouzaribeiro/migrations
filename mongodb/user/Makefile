migrateup:
	migrate -source file:// -database mongodb://root:root@springboot:27017/user?authSource=admin up 

migratedown:
	migrate -source file:// -database "mongodb://root:root@springboot:27017/user?authSource=admin" down 

.PHONY: migrateup migratedown
