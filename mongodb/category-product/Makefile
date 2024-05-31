migrateup:
	migrate -source file:// -database mongodb://root:root@springboot:27017/category_product?authSource=admin up 

migratedown:
	migrate -source file:// -database mongodb://root:root@springboot:27017/category_product?authSource=admin down 

.PHONY: migrateup migratedown
