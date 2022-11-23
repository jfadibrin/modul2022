# Melbourne Housing Snapshot

Snapshot of Tony Pino's Melbourne Housing Dataset

### Context
Melbourne real estate is BOOMING. Can you find the insight or predict the next big trend to become a real estate mogul… or even harder, to snap up a reasonably priced 2-bedroom unit?

### Content
This is a snapshot of a dataset created by Tony Pino.

It was scraped from publicly available results posted every week from Domain.com.au. He cleaned it well, and now it's up to you to make data analysis magic. The dataset includes Address, Type of Real estate, Suburb, Method of Selling, Rooms, Price, Real Estate Agent, Date of Sale and distance from C.B.D.

### Notes on Specific Variables
| Variable  | Definition  |
|-----------|-------------|
| Rooms | Number of rooms |
| Price | Price in dollars |
| Method | S - property sold; <br> SP - property sold prior;<br> PI - property passed in;<br> PN - sold prior not disclosed;v SN - sold not disclosed;<br> NB - no bid;<br> VB - vendor bid;<br> W - withdrawn prior to auction;<br> SA - sold after auction;<br> SS - sold after auction price not disclosed.<br> N/A - price or highest bid not available.|
| Type | br - bedroom(s);<br> h - house,cottage,villa, semi,terrace;<br> u - unit, duplex;<br> t - townhouse;<br> dev site - development site;<br> o res - other residential.|
| SellerG | Real Estate Agent |
| Date | Date sold |
| Distance | Distance from CBD |
| Regionname | General Region (West, North West, North, North east …etc) |
| Propertycount | Number of properties that exist in the suburb. |
| Bedroom2  | Scraped # of Bedrooms (from different source) |
| Bathroom | Number of Bathrooms |
| Car | Number of carspots |
| Landsize | Land Size |
| BuildingArea | Building Size |
| CouncilArea | Governing council for the area |

### Acknowledgements
This is intended as a static (unchanging) snapshot of https://www.kaggle.com/anthonypino/melbourne-housing-market. It was created in September 2017. Additionally, homes with no Price have been removed.