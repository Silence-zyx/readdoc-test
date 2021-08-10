.. BookTest documentation master file, created by
   sphinx-quickstart on Tue Aug  3 10:22:50 2021.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

This is a test
==================================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

Locat
================
For example:

.. code-block ::

   contract Demo { // contract field identifier

    final address _owner; // local variables
    mapping(address => uint256) pubBalances; // mapping entries
    	function pubBalanceOf(address owner) public view returns (uint256) { // function arguments
    	    return pubBalances[owner];
    	}
    }


   Chapter1/index
   about
   
