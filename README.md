# TIMP_1

**Задание_1**
`wget https://sourceforge.net/projects/boost/files/boost/1.69.0/boost_1_69_0.tar.gz`

**Задание_3**
`tree boost_1_69_0 -L 1`

**Задание_4**
`tree ~/boost_1_69_0`

**Задание_5**
`find . -name "*.h" | wc -l`
`find . -name "*.hpp" | wc -l`
`find . -name "*.cpp" | wc -l`
`find . -not \( -name "*.h" -o -name "*.hpp" -o -name "*.cpp" \) | wc -l`

**Задание_6**
`find . -name 'any.hpp'`

**Задание_7**
`grep -lr boost::asio`

**Задание_8**
`./bootstrap.sh --prefix=boost_output`
`./b2 install`

**Задание_9**
`mkdir ~/boost-libs`
`mv * ~/boost-libs`

**Задание_10**
`ls -hl`

**Задание_11**
`find . -type f -exec du -h {} +|sort -rh | head -n 10`
