Gibberish AES Codeigniter version
=================================

This is the codeigniter version of gibberish aes php library created by ivantcholakov (see https://github.com/ivantcholakov/gibberish-aes-php)

It is compatiple with AES javascript encryption library, https://github.com/mdp/gibberish-aes


Usage
=====

you need to keep a private key for encryption and decryption
you can set that in your config file for project wide usage


<pre>
Load GibberishAES library in your conroller

$this->load->library('GibberishAES');
</pre>
<pre>
//Encrypt 

$encrypted_string = $this->gibberishaes->enc('string to encrypt', 'your private key');
</pre>
<pre>
//Decrypt

$decrypted_string = $this->gibberishaes->dec($encrypted_string, 'your private key');
</pre>
