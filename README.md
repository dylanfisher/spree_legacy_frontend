> This version of the Spree (Legacy) Frontend is customized to exclude all but the core frontend functionality
> needed to run a Spree store in a custom host app. This is helpful to avoid name collisions in helpers and
> exclude other functionality not necessary in a more custom setup.

# Spree (Legacy) Frontend

This is the old Spree Storefront extracted from Spree < 4.3.

## Installation

Add

```ruby
gem "spree_frontend", "~> 4.4.0", git: "https://github.com/dylanfisher/spree_legacy_frontend.git", branch: "4-4-stable"
```

to your `Gemfile`.

Run:

```bash
bundle install
bin/rails g spree:frontend:install
```

## Maintanence policy

This gem is in maintainence mode.

We only accept bug fixes, Spree/Rails compatibility improvements & security patches.

For new project we recommend using [Storefront API](https://api.spreecommerce.org/) to create your own unique storefront or use one of the pre-built starters: 

* [Next.js](https://dev-docs.spreecommerce.org/storefronts/next.js-commerce)
* [Vue Storefront](https://dev-docs.spreecommerce.org/storefronts/vue-storefront)

## Customization

[Developer documentation](https://dev-docs.spreecommerce.org/customization/storefront)
