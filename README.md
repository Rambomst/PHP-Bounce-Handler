PHP Bounce Handler
===================

## Usage

#### Parse Email

```
use rambomst\PHPBounceHandler\BounceHandler

$bounce_handler = new BounceHandler();
$parsed_bounce_email = $bounce_handler->parseEmail($email);
```

#### Search For Custom Header

```
$custom_header = $bounce_handler->findXHeader('X-Custom-Identifier')
```

## License

This library is under [BSD License](LICENSE).