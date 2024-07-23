# Cedric-Links
![Preview](/assets/preview.png)

Website for my portfolio.
>Tutorial thanks to [How to Become a Developer](https://www.youtube.com/@howtobecomeadeveloper)

## Installation

Use docker and httpd, build the image by using the command below.

```bash
sudo docker build -t cedric-links .
```
Deploy with docker container
```
sudo docker run -itd -p 3080:80 --name cedric-links cedric-links
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)