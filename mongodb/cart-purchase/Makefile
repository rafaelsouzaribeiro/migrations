migrateup:
	migrate -source file:// -database mongodb://root:root@springboot:27017/cart_purchase?authSource=admin up 

migratedown:
	migrate -source file:// -database mongodb://root:root@springboot:27017/cart_purchase?authSource=admin down 

.PHONY: migrateup migratedown
