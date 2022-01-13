# LEMP-Stack

Simple ansible playbook that install LEMP stack on centos7 (Nginx+PHP7+MariaDB)
This is a very primitive version, made during training.
It currently contains only sample bootstrap template and php-info page. MariaDB is working, but not using in this version.


## Installation

1. Clone this repo
2. Change destination host and credentials in `hosts.ini` file
3. Run playbook with command `ansible-playbook playbook.yml -i hosts.ini`
4. Done. Open in browser `http:\\destination_host\` for sample page or `http:\\destination_host\info.php` to insure that php is work
