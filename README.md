kdog
====

kdog is a Drupal module which provides a function to pretty print (krumo, courtesy of devel) dumps into watchdog.

It provides one useful function, namely kdog().

    /**
     * watchdog() replacement which behaves more like dpm().
     *
     * @param mixed $input Any input you would usually pass as the first parameter
     *  to dpm().
     * @param string $name The very first portion of the logged message.
     * @param constant $severity One of the WATCHDOG_* severity levels.
     */
    function kdog($input, $name = 'kdog debug output', $severity = WATCHDOG_DEBUG)
