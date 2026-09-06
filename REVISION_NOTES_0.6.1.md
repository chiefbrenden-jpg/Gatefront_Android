# Gatefront 0.6.1 — five-pass market-readiness update

1. **Containment:** clamps every enemy to the road, repairs invalid positions, pulls stragglers into combat after the course ends, and allows battle tanks to enter the engagement formation.
2. **Movement:** forward-only approach velocity and animation timing driven by actual distance travelled, eliminating reverse floating and time-based moonwalking.
3. **Animation:** continuous weight transfer and eased transforms for troops; cross-faded Iron Warlord and Alien Emperor frames to create in-between motion instead of hard pose cuts.
4. **Progression:** three Combat Armour tiers costing 20,000, 100,000 and 250,000 coins, reducing combat losses by 18%, 36% and 54%.
5. **Store scaffold:** four coin products, native billing request bridge, idempotent verified-purchase callback, and refreshed UI. Product IDs must be created in Google Play Console and the native BillingClient connected before release.

## Validation

- JavaScript syntax checked with Node.
- Required alien, boss, troop and tank assets checked in the Android assets tree.
- Android application ID and release signing identity retained for update compatibility.
