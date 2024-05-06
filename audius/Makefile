# Default target
.PHONY: all
# all: slither

# Target to run Slither
.PHONY: slither
all:
	slither-check-upgradeability src/staking.sol Staking --proxy-filename src/proxy.sol --proxy-name AudiusAdminUpgradeabilityProxy
