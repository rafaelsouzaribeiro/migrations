migrateup:
	migrate -source file:// -database mongodb://root:root@springboot:27017/contact_adm?authSource=admin up 

migratedown:
	migrate -source file:// -database mongodb://root:root@springboot:27017/contact_adm?authSource=admin down 

.PHONY: migrateup migratedown
