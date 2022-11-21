# kvoltz
CHANGELOG
Version 2 - Main

BEP20: Internal Function "_burn" removed.
BEP20: Every "owner" renamed to "owner_".
BEP20: Pragma locked to 0.8.17 from ^0.8.17.

Kvoltz: Zero Address validation added.
Kvoltz: Maximum tax amount limited to 25%.
Kvoltz: Function "setTaxWallet(address)" now also sets "isTaxWallet[] = true".

KvoltzVesting: The following events have been added:
    event KvoltzAddressUpdated(address _kvoltzTokenAddress);
    event BUSDAddressUpdated(address _busdTokenAddress);
    event AdminStatusSet(address _address, bool _status);
    event SeedSalePurchased(uint _amount, address _address);
    event PrivateSalePurchased(uint _amount, address _address);
    event AdvisorsAdded(uint[] _amountKVZ, address[] _address);
    event AirdropAdded(uint[] _amountKVZ, address[] _address);
    event SeedSaleStatusChanged(bool _bool);
    event PrivateSaleStatusChanged(bool _bool);
    event TokenGenerationEventStarted();
    event TokensDistributed();
