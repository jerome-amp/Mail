# YouTube

```

require 'Mail.php';

(new Mail())
->to('rick@astley.com')
->cc('rick@astley.com')
->bcc('rick@astley.com')
->from('Rick Astley', 'rick@astley.com')
->reply('Rick Astley', 'rick@astley.com')
->subject('Never Gonna Give You Up')
->message('<img src="cid:image.jpg">')
->priority('high')
->attachment('file', 'song.mp3', $song)
->attachment('image', 'image.jpg', $image)
->send();

```

## Author

**Jérôme Taillandier**

## License

This project is licensed under the WTFPL License - see the [LICENSE.md](LICENSE.md) file for details
