run:
	harp server --port 8080

deploy:
	rsync -rv --exclude='.git/' . ../../../Documents/Resume/alpenglow
	cd ../../../Documents/Resume/alpenglow && git add -A
	cd ../../../Documents/Resume/alpenglow && git commit -am "Updated Alpenglow demo"
	cd ../../../Documents/Resume && git push origin master

