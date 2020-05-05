# ufc-event-notifier

The project's goal is to deliver the latest UFC event information via a WhatsApp message.

### Prerequisites

A Twilio account is required and a scheduling method. I used IBM Data Studio scheduler to run every Friday.


### Installing

After setting up a Twilio account, add the your Twilio ID, Authorisation Token, the 'from number' and the 'recepient' number to the code.

```
account_sid = '' # enter Twilio ID
auth_token = '' # enter Twilio Authorisation Token
from_='whatsapp:+' # Twilio phone number
recipient = 'whatsapp:+' # Recipients phone number
```

Then run using a schdeuler.

## Built With

* [Beautiful Soup 4](https://www.crummy.com/software/BeautifulSoup/bs4/doc/) - For webscrapping from Wikipedia
* [Twilio](https://www.twilio.com/) - To deliver WhatsApp messsages
* [Jupyter Notebooks](https://jupyter.org/) - Where code was written.


## Authors

* **James Nanji** - [ninjananjo](https://github.com/ninjananjo)
