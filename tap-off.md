
# Tap-off

When creating a manufacturing setup, add tap-off points which collect the intermediate products into a standard storage container.  This gives you the ability to pull out those for ad-hoc projects without having to manually craft everything.  A good example of this is iron plate construction.

NOTE: Tap-off points are really meant for handcrafting needs.

## Naive Approach

This setup works fine for constructing the final product (iron plate) but it's difficult to skim off any raw/intermediate products for ad-hoc needs.

```
Miner -> Smelter -> Constructor -> Storage
```

## Tap-Off Approach

With the splitter approach, 50% of the miner production will be redirected into storage until the storage unit is full.  Once the storage unit fills up, all production goes to the smelter.

This gives you the ability to access raw iron ore, iron ingots and the final iron plates at a later point.  Maybe you need to make steel later and need raw ore.  Or you need to grab ingots to make some of something else.

```
Miner -> Splitter -> Smelter -> Splitter -> Constructor -> Storage
            |                      |
            +--> Storage           +--> Storage
```


