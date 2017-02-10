nusoap
======

Nusoap PHP library

<b>To implement soap server with simple or digest auth:</b>


    if (soap_transport_http::authenticate("username", "password")) // checkes for both simple and digest
    {
        $result = array('QueryStatus' => '200', 'QueryMsg' => 'Logged in successfully');
    } else
    {
        $result = array('QueryStatus' => '900', 'QueryMsg' => 'Forged user');
    }
Copy of original library for supporting packagist composer.

More info at project webite http://nusoap.sourceforge.net/


