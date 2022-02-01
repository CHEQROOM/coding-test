# Technical test

## What we want you to build

As CHEQROOM, we are focused on managing equipment and allowing users to reserve equipment in their inventory. For this assignment, we want you to build a mini-CHEQROOM, where you can create a reservation with items that are available in your own inventory.

## How we want you to build it

We want you to create a new reservation with items from your inventory. To make it a bit more challenging, we have set the following business rules:

- A reservation has a name.
- A reservation has a from and to date.
  - Both dates are in the future.
  - To date is after the from date.
- You can add items to your reservation by selecting equipment from your inventory.
- The selected items are grouped by category.

Once everything has been filled in, you can create a reservation with the name, dates and items that you have selected.

To make this task a bit easier (and so you don't have to create your own API), we have provided a JSON file with items from your inventory. You can also assume that creating a reservation will always succeed.

While these are shortcuts you are allowed to take, make sure that it is easy to connect with a real API in the future. We don't want to re-write the entire application just to fetch real data.

You are free to choose which tools and packages you use to achieve this task, but make sure you have solid argumentation for your choices. The only requirement is that you use React (and preferably TypeScript).

## Problems?

If something is not clear or if you have other questions, feel free to contact us at <engineering@cheqroom.com>.
