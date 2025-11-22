# add-function-Array
  function getUserArray(
        address _user
    ) external view override returns (Arrays[] memory) {
        return Peer[_user];
      }
