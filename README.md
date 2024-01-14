## canAccess Function

# Overview

~ The canAccess function is designed to determine whether a user has access based on their subscription status. It takes two parameters:

~ purchasedSubscription (boolean): Indicates whether the user has a purchased subscription.

~ freeTrial (boolean): Indicates whether the user is on a free trial.
The function returns true if the user has either a purchased subscription or is on a free trial. Otherwise, it returns false.


# Usage

~ Input
purchasedSubscription (boolean): Set to true if the user has a purchased subscription, otherwise false.
freeTrial (boolean): Set to true if the user is on a free trial, otherwise false.

~ Output
true: If the user has a purchased subscription or is on a free trial.
false: If neither a purchased subscription nor a free trial is present.
