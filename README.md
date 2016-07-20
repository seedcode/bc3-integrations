# Basecamp 3 Integrations

Does your service integrate with the [Basecamp 3 API](https://github.com/basecamp/bc3-api)? Would you like to have it listed on [basecamp.com](https://basecamp.com)? Then you're in the right place.

**Note: We don't have a page for Basecamp 3 integrations [like we do for Basecamp 2](https://basecamp.com/2/extras) yet. Add your service now to be included when it's ready.**

## Add Your Integration

To add your integration, please open a pull request.

Edit [integrations.yml](integrations.yml) and add a new entry to the bottom of the list.

Include the `name`, `description`, `website`, `icon`, and `category`. Categories are identified at the top of [integrations.yml](integrations.yml).

Example:
```yaml
-
  name: "Basecamp 3 App"
  description: "Basecamp 3 for Mac and Windows"
  website: "https://basecamp.com/3/via"
  icon: "basecamp3.png"
  category: 1
```

Add your icon file to the [icons/](icons/) folder. Icons must be `256x256` in `.png` format.

Thank you!
