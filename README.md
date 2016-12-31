# zend-framework-logger-ci-library
CodeIgniter 3 Wrapper Library for Zend Framework Logger

Usage:
# Initialize log for use
$this->load->library('zend');
$this->zend->log_init('my.custom.log');

# Logging info messages
$this->zend->log_info('This is Info message');
$this->zend->log('This is Info message', Zend_Log::INFO);
# Logging error messages
$this->zend->log_error('This is Error message');
$this->zend->log('This is Error message';
