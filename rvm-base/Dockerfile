FROM mdxp/base

ENV PATH /usr/local/rvm/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
RUN echo 'gem: --no-ri --no-rdoc' > /etc/gemrc

RUN curl -L https://get.rvm.io | bash -s stable

ENV RVM_INSTALL_RB_VERSION 2.1.2
RUN /bin/bash -l -c 'source /etc/profile.d/rvm.sh && rvm install $RVM_INSTALL_RB_VERSION'
