docker:
	docker build -t jarvis/text-to-speech .

run:
	docker run --rm -i -t \
	 -v $(PWD):/usr/text-to-speech \
	 -w /usr/text-to-speech \
	 jarvis/text-to-speech